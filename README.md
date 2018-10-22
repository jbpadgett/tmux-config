TMUX Config File
========================

##Using the global TMUX config file
```
git clone https://github.com/jbpadgett/tmux-config.git
cp .tmux.conf.local ~/
``` 

##Usage Notes 
Using tmux config from: ```https://github.com/gpakosz/.tmux``` 
The tmux config file from ```@gpakosz``` is used to provide visual features like the powerline theme. 
As a pre-requisite, the following additional steps must be done:  
1. Clone the ```https://github.com/gpakosz/.tmux``` repo. 
2. Keep a symlink to ```~.tmux/.tmux.conf``` to enable git pull updates. 
3. Customize only the ```~/.tmux.conf.local``` which is merged into the main one. 
    a. The customizations I use are in ```~/.tmux.conf.local``` which include things like:  removing battery indicator, enabling osx copy/paste. 



