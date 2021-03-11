  
![image](https://github.com/MichalonCarpino/Tools_Legal_Utilisation/blob/main/Tools_Legal_Utilisation/VirusTotal/Capture2.PNG)

VIRUSTOTAL:
Après avoir récupéré différents types de malware sur la plateforme “any run”, nous avons voulu essayer d’analyser ces derniers via VirusTotal.
Pour rappel VirusTotal est un site web qui analyse les fichiers suspects et facilite la détection rapide des virus, vers, chevaux de troie et toutes sortes de logiciels malveillants détectés par les moteurs antivirus.

-DEBUT-
VIRUSTOTAL:
After recovering different types of malware on the "any run" platform, we wanted to try to analyze them via VirusTotal.
As a reminder, VirusTotal is a website that analyzes suspicious files and facilitates the quick detection of viruses, worms, trojans and all kinds of malware detected by antivirus engines.
-FIN-

Procédure suivie :
téléchargeons sur la plateforme les malwares sous format .zip
pour chaque fichier, extraire le fichier suspect,
sur le site VirusTotal : sélectionner le fichier 
lancer l’analyse et observer l’analyse du site

--debut--

Procedure followed :
- let's download on the platform the malwares in .zip format
- for each file, extract the suspect file,
- on the VirusTotal website: select the file 
- launch the analysis and observe the analysis of the site

--fin--

Voici un aperçu du rendu d’analyse de VirusTotal :


Les échantillons sélectionnés sont de format : pdf, .exe, .bin, .xlsm, .ace
Analyse d’un fichier : 

type : exe
type malware : Troyan
nbr d’antivirus détécté : 59/ 71
graphe de relation du malware :

--debut--
Here is an overview of the VirusTotal analysis:


The selected samples are in the following formats: pdf, .exe, .bin, .xlsm, .ace
Analysis of a file : 
type: .exe
malware type : Troyan
Number of antivirus which detected : 59/71
Graph of relation of malware:


--fin--






Après analyse des 5 fichiers nous pouvons constater :
les antivirus qui détecte le plus sont : AVG, BitDenfender theta, McAfee-GW-Edition, Fortinet
sachant que l’analyse s’effectue sur une route précise au lancement de l’analyse, il apparaît quelques fois des différences de résultat pour le même fichier mais pour deux analyses différentes (ex: le nbr d’antivirus varie d’une analyse à une autre)

--deb--
After analysis of the 5 files we can see :
the antiviruses that detect the most are: AVG, BitDenfender theta, McAfee-GW-Edition, Fortinet
knowing that the analysis is carried out on a precise route at the launching of the analysis, it appears sometimes differences of result for the same file but for two different analyses (ex: the number of antivirus varies from one analysis to another)
--fin--

