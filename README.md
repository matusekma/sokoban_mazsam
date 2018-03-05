# Killer Sokoban
Mazsam csapat:
	* Zs�fi
	* �kos
	* �d�m
	* Mil�n
	* Marci


# Git
## Telep�t�s
https://git-scm.com/download/win
FONTOS!!! 
Run Git and included Unix tools from the Windows Command Prompt opci�t v�lassz�tok

## Git Bash seg�ts�g:
* git init <directory> - l�trehoz egy mapp�t, ahol dolgozhattok
* cd <directory> - �tv�lthatsz erre a mapp�ra
* git clone <url> - a projekt lekl�noz�sa saj�t magatoknak, ezt kezditek el m�dos�tani, �s majd tolj�tok fel a m�dos�t�sokat
* ls -l - kilits�zza a mappa tartalm�t, amiben vagy
* git config --global user.name "Gipsz Jakab" - username be�ll�t�sa
* git add <filen�v> - �j f�jlt ad hozz� a commitoland� f�jlok k�z� (homokoz� a neve, angolul index)
* git status - meg tudod n�zni a hozz�adott f�jlokat
* git commit -a - sz�vegf�jlban megmutatja a commitoland� f�jlokat
* git commit -m "�zenet" - valamilyen �zenettel commitolja (bet�lti) az index tartalm�t a lok�lis repositoryba
* git log --oneline --graph --decorate - sz�pen gr�fosan kirajzolja a commitokat

## Az online repository be�ll�t�sa:
* git clone <url> - EZZEL �RDEMES KEZDENI
* git remote add origin <url, ami a projekt url-je, ahova pull requestet szeretn�l> 
* git remote -v - a remoteok st�tusza

## Felt�lt�s az online repositoryba:
* git pull origin master - a m�sok �ltal v�grehajtott v�ltoztat�sok let�lt�se
* git push origin master - a mi v�ltoztat�saink �letbe l�ptet�s�nek k�relme



