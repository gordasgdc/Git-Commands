Git Commands
============

## Versiune Tradusa
- [Versiune in romana](READMEro.md)

___

_O listă a comenzilor mele frecvent utilizate in Git_

--

### Obținerea și crearea de proiecte

| Comanda | Descriere |
| ------- | ----------- |
| `git init` | Inițializați un depozit local Git |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Creați o copie locală a unui depozit de la distanță |

### Instantanee de bază

| Comenzi | Descriere |
| ------- | ----------- |
| `git status` | Verifica statusul |
| `git add [file-name.txt]` | Adăugați un fișier în zona de înscenare |
| `git add -A` |Adăugați toate fișierele noi și modificate în zona de înscenare |
| `git commit -m "[commit message]"` | Commit schimbări |
| `git rm -r [file-name.txt]` | Eliminați un fișier (sau folder) |

### Branching & Merging

| Comanda | Descriere |
| ------- | ----------- |
| `git branch` | Listeaza branches (asteriscul denumește ramura actuală) |
| `git branch -a` | Enumerați toate branches (locale sau remote) |
| `git branch [branch name]` | Creaza un nou branch |
| `git branch -d [branch name]` | Ștergeți un branch |
| `git push origin --delete [branch name]` | Șterge un remote branch |
| `git checkout -b [branch name]` | Creaza un nou branch și treceți la ea |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git branch -m [old branch name] [new branch name]` | Redenumeste a local branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Aruncați modificările la un fișier |
| `git merge [branch name]` | Fuzionează un branch într-un  branch activ |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing și actualizarea Proiectelor

| Comanda | Descriere |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspecție și comparație

| Comanda | Descriere |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git log --oneline` | View changes (briefly) |
| `git diff [source branch] [target branch]` | Preview changes before merging |
