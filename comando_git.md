jfranquis@DESKTOP-0V93NQJ MINGW64 ~/Desktop (master)
$ cd labenu/
bash: cd: labenu/: No such file or directory

jfranquis@DESKTOP-0V93NQJ MINGW64 ~/Desktop (master)
$ ls
'Código Preto - Desafio de Programação.pdf' 'Fallout Shelter.url' Notion.lnk\* desktop.ini visualg3.0.7/

jfranquis@DESKTOP-0V93NQJ MINGW64 ~/Desktop (master)
$ d/
bash: d/: No such file or directory

jfranquis@DESKTOP-0V93NQJ MINGW64 ~/Desktop (master)
$ cd /d

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ ls
'$RECYCLE.BIN'/ Documents/ NLW4/ 'Video Labenu'/ jfranquis/ swiftshader/
BackupJanaina16_06.rar Download/ Nilton.rar WUDownloadCache/ maratona-discover/ temp/
Balneário.rar DumpStack.log.tmp Pictures/ Whats/ projeto-1/ vendor/
Config.Msi/ 'Imagem SO VirtualBox'/ 'Program Files'/ WindowsApps/ projeto-ctt-1/ yarn.lock
DeliveryOptimization/ Labenu/ Recovery/ WpSystem/ projetos/
'Digital House - Código Preto'/ 'Labenu Aulas'/ Sensedia/ campinas-t-talents/ resources/
Discover/ MapData/ 'System Volume Information'/ ctt-node-js-basico/ sqlite/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ cd labenu/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/labenu (master)
$ ls
Exercicios/ 'Rotina*labenu_Onboarding-01*(1).jpg' aula1/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/labenu (master)
$ cd ..

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ cd labenu_aulas/
bash: cd: labenu_aulas/: No such file or directory

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ cd Labenu Aulas/
bash: cd: too many arguments

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ cd Labenu_Aulas/
bash: cd: Labenu_Aulas/: No such file or directory

jfranquis@DESKTOP-0V93NQJ MINGW64 /d (master)
$ cd Labenu_Aulas/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas (master)
$ ls
semana-0/ semana-1/ semana-2/ semana-3/ semana-4/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas (master)
$ cd semana-0

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0 (master)
$ ls
aula-1.md aula-2.md aula-paiva/ aula1-git.md projeto/

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0 (master)
$ cd aula-paiva

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ ls
README.md

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ ls -a
./ ../ .git/ README.md

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ touch comando_git.txt

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ ls
README.md comando_git.txt

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ ls
README.md comando_git.txt

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
(use "git add <file>..." to include in what will be committed)
comando_git.md

nothing added to commit but untracked files present (use "git add" to track)

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git add .

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: comando_git.md

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git commit -m "comandos Git Aula-1"
[main 9408f5f] comandos Git Aula-1
1 file changed, 82 insertions(+)
create mode 100644 comando_git.md

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
(use "git push" to publish your local commits)

nothing to commit, working tree clean

jfranquis@DESKTOP-0V93NQJ MINGW64 /d/Labenu_Aulas/semana-0/aula-paiva (main)
$ git log
commit 9408f5f045f175cc5f306cd42031b2fbeedd6550 (HEAD -> main)
Author: Janaina Franquis <39539970+jfranquis@users.noreply.github.com>
Date: Thu Apr 1 09:54:26 2021 -0300

    comandos Git Aula-1

commit aee06a6c8e46d0cd05157b93f6d81e4754e0ec6b (origin/main, origin/HEAD)
Author: Janaina Franquis <39539970+jfranquis@users.noreply.github.com>
Date: Thu Apr 1 09:24:38 2021 -0300

    Initial commit
