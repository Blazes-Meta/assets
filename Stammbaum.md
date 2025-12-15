```mermaid
---
config:
    flowchart:
        curve: basis
        nodeSpacing: 10
        rankSpacing: 50
        padding: 6
    theme: dark
    themeVariables:
        edgeLabelBackground: '#1f1f1fff'
        clusterBkg: '#953030ff'
        clusterBorder: '#451414ff'
---
flowchart BT

Annhilati[Anton]
Annhilati -- McCreator Discord ---> controllmaster[Viko]
Annhilati -- THeJoCraft Discord ---> Wasserschaden[Damian Lunginbühl]
Wasserschaden --> MinMag
controllmaster --> Hacki
controllmaster --> Mesi_Legends

%% BEGINN Kontext St. Benno Gymnasium

Annhilati --> kl27a

subgraph StBennoGymnasium [St. Benno Gymnasium]
    subgraph kl27a [Klasse Abi '27 a]
        laemmicore[Markus]
        joshi[Josua]
        Pringelchen[Kolja]
        brokkoli[Alex]
        nocki[Anselm]
        laserlink[Leonhard]
        ralfopro[Ralf]
    end
    Syntheria
    Feite
    PearlyPinky[Keon]
    Matthias
end
Syntheria --> FAnton

joshi --> Schlapperklange

%% ENDE Kontext St. Benno Gymnasium
%% BEGINN Kontext 96. GS

Annhilati[Anton] ---> 96Grundschule

subgraph 96Grundschule [96. GS]
    subgraph 96GSxTolkewitz [ ]
        Malte
        Fionn[ichbineindino]
    end
    Tony[Snerz]
    Matteo
    Tom
end

%% ENDE Kontext 96. GS
%% BEGINN Kontext Tolkewitz

Malte --> lurzz
lurzz --> dopesince[Paul]
96GSxTolkewitz --> TolkewitzerGymnasium

subgraph TolkewitzerGymnasium [Tolkewitzer Gymnasium]
    RandomDude[Friedrich]
    GermanDaddy[Richard]
    Florian
    Creepnox[Maurice]
end
Creepnox --> speakbleyt[Paul]
Florian --> Henri

%% ENDE Kontext Tolkewitz

subgraph LRSSchule [LRS-Schule]
    lurzz[Lennart]
    gardine[Rouven]
    Danilo[Danilo]
end

%% BEGINN Kontext BasisZock

Henri --> BasisZock
BasisZock --> BasisZockViewer
BasisZock -- Valorant --> FAnton
BasisZock --> TheVoid[Julius]
BasisZock --> Bioladen
BasisZock -- Grundschule --> SirHelius[Marek]
BasisZock -- Grundschule --> Googelha[Georg]
subgraph BasisZockViewer [ ]
    AnnanasTV
    MoritzTheEdgelord
end

AnnanasTV --> Zero
AnnanasTV --> RonjaRonjason
AnnanasTV --> Momo

%% BEGINN Kontext Comfy

Annhilati --> Comfy
Comfy --> Crafter
Comfy --> luke
Comfy --> Ferdi
Comfy --> Otal
Comfy --> Slayjanhd
Comfy --> Xwink[X-wink]
Comfy --> Arabroke['Schnitzel Man']

%% ENDE Kontext Comfy
```