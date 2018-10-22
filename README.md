TMUX Config File
========================

##Using the global TMUX config file
```
git clone https://github.com/jbpadgett/tmux-config.git
cp .tmux.conf ~/
```
##Usage Notes
Using tmux config from: https://github.com/gpakosz/.tmux
The tmux config file from ```@gpakosz``` is used to provide visual features like the powerline theme.
As a pre-requisite, the following additional steps must be done.
0. Clone the https://github.com/gpakosz/.tmux repo.
1. Keep a symlink to ```~.tmux/.tmux.conf``` to enable git pull updates.
2. Customize only the ```~/.tmux.conf.local``` which is merged into the main one.
    a. The customizations I use are in ```~/.tmux.conf.local``` which include things like:  removing battery indicator, enabling osx copy/paste.



##Initialize custom session configs
```
bind S source-file ~/.tmux/session1  
bind s source-file ~/.tmux/session2  
```



