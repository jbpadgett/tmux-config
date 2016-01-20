TMUX Global Config File
========================

##Using the global TMUX config file
```
git clone https://github.com/jbpadgett/tmux-config.git
cp .tmux.conf ~/
```

##Usage Notes
Put everything global here:   ~/.tmux.conf  
Put environment specific tmux config here:   ~/.tmux/<purposename>  

*Example:*
```
~/.tmux/chef  
~/.tmux/myproject  
```

##Initialize custom session configs
```
bind S source-file ~/.tmux/session1  
bind s source-file ~/.tmux/session2  
```



