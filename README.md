### Gioia Chen 5BT-i

# Elenco delle Pagine
- Homepage (index.html)
- Tabella Orari (programmazione.html)
- Prenotazione Biglietti (prenota.html)
- Contatti (contatti.html)

## Comandi Git

User/author configuration
$ git config user.name "rxiliv"
$ git config user.mail "05gioia.chen20@gmail.com"

GitHub account login
$ gh auth login

Initialize folder as Git folder (with history)
$ git init

Open folder with VS Code
$ code .

Add files for the next commit
$ git add index.html

Commit added files with brief description
$ git commit -m "Add basic structure of homepage"

Create repository
$ gh repo create supermovies --public --source=. --remote=origin --push

Push commits on the repository
$ git push