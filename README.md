# hello-github
Estudando este VCS 

Busco Entender no SCM
* Gerenciamento de BRANCHS(versões)
* Uso de TAGS

usar na plataforma github
* Github Pages
* issues
* branchs
* ~~atualizar de/para repositórios loca~~
* tipos de repositórios

Prioridades
* Formas de tratar conflitos durante merge
* diferenças fetch/pull 

shortcuts 
* pull/fetch baixa atualizações do remoto
* push envia atualizações para remoto
* 

Alguns comandos
git log --date=short --format="%ci"|awk '{print $1}'|uniq # Which days I've worked
git log --author=$USER --format="- %B" --since=-7days --reverse |mail -s "What I've done this week" boss@company\.com
git log | awk '/Date/{print " : " $4 " " $3 " " $6}' | uniq -c # To print commits per day for a git repo.
git log --pretty=format:'%s'|cut -d " " -f 1 |sort|uniq -c|sort -nr # Show a ranked count of git verbs
