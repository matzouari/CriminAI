# Instructions d'installation du logiciel

  1. Assurez-vous d'avoir bien Python et Pip installés sur votre machine ;
  2. Ouvrir un terminal ;
  3. Aller dans le dossier où on veut mettre l’application ;
  4. Créer un environnement virtuel : `python3 -m venv CriminAI` ;
  5. Aller dans l’environnement virtuel : `cd CriminAI` ;
  6. Activer l’environnement virtuel : `source bin/activate` ;
  7. Créer un fichier avec l’extension .py : `touch appli.py` (le nom `appli` peut changer ; il ne faut juste pas que le nom soit le même que celui du package, à savoir CriminAI.py) ;
  8. L’ouvrir et écrire ces deux lignes : <br>
  `from CriminAI import mainWindow`<br>
  `mainWindow()` ;
  9. Enregistrer et fermer le fichier ;
  10. Si vous êtes sur Mac, dans le terminal, taper `/Applications/Python` et faire `tab` pour que le terminal autocomplète avec la bonne version de Python, puis ajouter `/Install\ Certificates.command`. <br>
  Cela donne par exemple pour Python 3.12 : `/Applications/Python\ 3.12/Install\ Certificates.command` ;
  11. Puis installer le package via PyPi : `pip install CriminAI` ;
  12. Enfin, lancer l'application : `python3 appli.py` (pour notre cas, adapter le nom en fonction).
