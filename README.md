# gitconfig
My Git Configuration

```
[color]
	ui = auto
[alias]
	st = status
	pl = pull --ff-only
	ps = push
	co = checkout
	ci = commit
	df = difftool
	cp = cherry-pick
	ca = commit --amend
	br = branch
	l = log --stat
	last = log -1
	lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
	up = push --set-upstream origin
	uf = push origin -f
	lf = log --follow -p
	aa = ls-files --modified
	su = status -uno
	cm = commit -m
	cl = clean -fdx
	fe = fetch --prune
	cc = cherry-pick --continue
	cf = clean -fdx
	bd = branch -D
	cb = checkout -b
    ap = add -p
    ri = rebase -i
    rc = rebase --continue
    ra = rebase --abort
    sp = stash pop
    ch = checkout
    rh = rebase
[push]
	default = simple
[core]
	editor = vim
	pager = less -+F
	longpaths = true
[diff]
	tool = meld
[difftool]
	prompt = false
[merge]
	tool = meld
```

difftool.prompt=false

merge.tool=meld

init.templatedir=~/.git_template

core.repositoryformatversion=0
