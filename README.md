## Fake news detection in Slovak on-line environment using deep learning methods
## Detekcia falošných správ v slovenskom online priestore pomocou metód hlbokého učenia

##### Autor  
Klaudia Ivancová



### Abstract
The diploma thesis deals with the detection of fake news on a specific domain, which is the Slovak language with the help of deep learning methods and specifically with the help of neural networks. The work is divided into theoretical and practical part, where the theoretical part deals to an overview of deep learning and deep neural networks and also a brief look at antisocial behavior and fake news occurring in the online environment. The practical part, in which various neural network architectures were used, deals with the detection of fake news. The work consists of two experiments, namely the detection of political and economical news and the detection of fake news focused on the topic of Covid-19.

### Abstrakt
Diplomová práca sa venuje detekcii falošných správ na špecifickej doméne, ktorou je slovenský jazyk za pomoci metód hlbokého učenia, a to konkrétne pomocou neurónových sietí. Práca je rozdelená na teoretickú a praktickú časť, kde teoretická časť je venovaná prehľadu o hlbokom učení, teda hlbokých neurónových sieťach a taktiež aj stručnému pohľadu na antisociálne správanie a falošné správy vyskytujúce sa v online prostredí. Detekcii falošných správ sa venuje praktická časť, v ktorej sa využili rôzne architektúry neurónových sietí. Práca pozostáva z dvoch experimentov a to detekcii politických a ekonomických správ a detekcii falošných správ zameraných na tému Covid-19.

### Dataset
https://drive.google.com/drive/folders/1ZNoSIKTkL6fo8Nag8JuVfbkeW0Rmbtm7?usp=sharing

### Spustenie kódu
Tento priečinok Fake-news-detection slúži na uloženie praktickej časti diplomovej práce, teda uloženie kódov. Práca je riešená ako výskumná úloha, ktorej prvotným cieľom je skúmanie rôznych modelov pri úlohe detekcie falošných správ. Výskumná úloha je orientovaná na detekciu falošných správ na špecifickej doméne, ktorou sú slovenské texty a táto úloha bola riešená pomocou vytvorenia modelov neurónových sietí a metód na automatickú identifikáciu falošných správ.

Riešili sme dokopy dva experimenty, kde v prvom sme sa zaoberali detekciou falošných politických a ekonomických správ a v druhom detekciou falošných správ zameraných na tému Covid-19. Obidva experimenty boli vyhotovené na množinách dát, ktoré obsahovali slovenské texty článkov zo slovenských internetových zdrojov.

V tomto priečinku môžeme vidieť dva podpriečinky, ktoré obsahujú kódy pre úlohu detekcie politických a ekonomických falošných správ a pre úlohu detekcie falošných správ zameraných na Covid-19. Pri obidvoch experimentoch sme množiny dát predspracovali dokopy trikrát, a to s ponechaním distribúcie cieľového atribútu s vymazanými stop slovami, s ponechanými stop slovami a s vybalansovaním trénovacej množiny s vymazanými stop slovami. Preto obidva podpriečinky disponujú tromi súbormi kódov. 

Úlohy boli riešené za pomoci programovacieho jazyka Python, kde sme využili aj prácu s knižnicami Tensorflow a Keras a kód bol vytváraný za pomoci Jupyter notebook prostredia. 
#### 1.
Pred prvotným spustením kódov je potrebné mať nainštalovaný jazyk Python a prostredie Jupyter notebook, ktoré sme my využívali prostredníctvom Anacondy. 
#### 2.
Na spustenie kódu budú potrebné tiež už spomenuté knižnice, ktoré sú vypísané na začiatku každého súboru. Avšak, pred ich úplne prvým použitím ich je potrebné nainštalovať, preto sa používa príkaz „pip install názov knižnice“ pre tých, ktorí s týmito knižnicami ešte nepracovali. 
#### 3.
A nakoniec pred samotným spustením je potrebné tiež stiahnuť dáta, na ktorých sa vykonáva detekcia správ. Vyššie je link, ktorý obsahuje súbory datasetov na stiahnutie. Po otvorení linku sa tam nachádzajú dva priečinky, kde v jednom je uložený dataset pre detekciu správ na tému Covid-19 a v druhom sú uložené dva datasety pre detekciu politických a ekonomických správ. 
