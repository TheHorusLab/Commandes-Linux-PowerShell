# PowerShell - Quête 1 </br>
### Commandes et équivalents Unix - PowerShell
<br>
<br>

**<ins>Les commandes Unix</ins>** 

<br> copier un fichier : cp (copy) **exemple**: cp fichier1 </br>
<br> supprimer un fichier : rm (remove) **exemple**: rm fichier1 </br>
<br> changer de répertoire : cd (change directory) **exemple**: cd /home/users/wilder/Téléchargements </br>
<br> créer un dossier : mkdir (make directory) **exemple**: mkdir dossier1 </br>
<br> manuel des commandes : man (manual) **exemple**: man ls </br>
<br> historique des commandes : history </br>
<br> créer un raccourci d'une commande :alias **exemple**: alias up="sudo apt update && sudo apt upgrade" </br>
<br> afficher le contenu d'un fichier: cat (concatenate) **exemple**: cat /home/users/wilder/fichier1 </br>

<br>
<br>

**<ins>Les commandes PowerShell</ins>**

<br> copier un fichier : Copy-Item **exemple**: Copy-Item "fichier1" -Destination "C:\Documents\dossier1" </br>
<br> supprimer un fichier : Remove-Item **exemple**: Remove-Item -Path 'C:\Windows\test1.txt </br>
<br> changer de répertoire : Set-Location **exemple**: Set-Location -Path C:\Documents </br>
<br> créer un dossier : New-Item **exemple**: New-Item -Path Dossier1 -ItemType Directory </br>
<br> manuel des commandes : Get-Help **exemple**: Get-Help Copy </br>
<br> historique des commandes : Get-History **exemple** : Get-History -Count 2 (ajout de l'argument -Count pour afficher l'historique des 2 dernières commandes) </br>
<br> créer un raccourci d'une commande : New-Alias **exemple**: New-Alias -Name "Shortcut" Get-Help </br>
<br> afficher le contenu d'un fichier: Get-Content **exemple**: Get-Content -Path "C:\Documents\test1.txt"</br>

<br>
<br>

**<ins> Les lignes de commandes utilisées pour trouver les cmdlets PowerShell</ins>**

Tentatives avec les commandes Unix --> Suggestions correspondantes proposées par PowerShell --> Vérifications avec l'argument -Online

<br> Get-Help cp </br>
<br> Get-Help Copy-Item -Online </br>
<br> Get-Help rm </br>
<br> Get-Help Remove-Item -Online </br>
<br> Get-Help cd </br>
<br> Get-Help Set-Location -Online </br>
<br> Get-Help mkdir </br>
<br> Get-Help New-Item -Online </br>
<br> Get-Help History </br>
<br> Get-Help Get-History -Online </br>
<br> Get-Help Alias </br>
<br> Get-Help New-Alias -Online </br>
<br> Get-Help cat </br>
<br> Get-Help Get-Content -Online </br>

