# gitconfig
My Git Configuration

color.ui=auto

alias.st=status

alias.pl=pull --ff-only

alias.ps=push

alias.co=checkout

alias.ci=commit

alias.df=difftool

alias.cp=cherry-pick

alias.ca=commit --amend

alias.br=branch

alias.l=log --stat

alias.last=log -1

alias.lg=log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit

alias.up=push origin

alias.lf=log --follow -p

alias.aa=ls-files --modified

alias.su=status -uno

alias.cm=commit -m

alias.uf=push origin -f

alias.cl=clean -fdx

alias.fe=fetch --prune

push.default=simple

core.editor=vim

core.pager=

diff.tool=meld

difftool.prompt=false

merge.tool=meld

init.templatedir=~/.git_template

core.repositoryformatversion=0
