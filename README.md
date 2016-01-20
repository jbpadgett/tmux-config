TMUX GLOBAL CONFIG FILE
========================

#Using the global TMUX config file
<pre><code>
https://github.com/jbpadgett/tmux-config.git

cp .tmux.conf ~/
</pre></code>  



#Usage Notes
Put everything global here:  ~/.tmux.conf  
Put environment specific tmux config here:  ~/.tmux/<purposename>  

*Example:*  
<pre><code>  
~/.tmux/chef  
~/.tmux/myproject  
</pre></code>  

# Initialize custom session configs
<pre><code>  
bind S source-file ~/.tmux/session1  
bind s source-file ~/.tmux/session2  
</pre></code>  



