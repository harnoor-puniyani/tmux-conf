## tmux-conf
___
 
Here we are trying to build a customised tmux as it is one of the most important tools that help you build things faster and its extensibly stable as compared to other tools , So i created a conf for helping myself out after sparing few hours , excatly how things work in here and determining to how to go about with it.So the steps are as follows :
1. Create a tmux conf 
``` bash
touch ~/.tmux.conf 
``` 
or to import defaults you can use in the tmux use
```bash
set options -g >~/.tmux.conf
```
In this file you can make 
2. Install the plugin manager for tmux , tpm is recommended.
[link][github - tpo]
[github - tpo]:https://github.com/tmux-plugins/tpm

3. to make the task more easier we will use Yank to make copy and paste easier between system clipboard and tmux clipboard.
You may find the 
[link]:https://github.com/tmux-plugins/tmux-yank 
