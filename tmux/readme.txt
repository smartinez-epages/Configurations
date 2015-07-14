
tmux

    Tmux is a "terminal multiplexer: it enables a number of terminals (or 
    windows), each running a separate program, to be created, accessed, 
    and controlled from a single screen. tmux may be detached from a screen
    and continue running in the background, then later reattached." 
    
    Official site and download : 
    
         	http://tmux.github.io
    
    Official documentation : 
    
            https://wiki.archlinux.org/index.php/Tmux
            
_____________________________________________________________________________
CONTENTS

    [doc]                           Documentation folder: Quick reference 
                                        in OpenOffice format (odt)
                                        
    [tmux.layouts]                  Scripts folder
    
    readme.txt                      This document
    
    tmux.conf                       The Zengui's tmux configuration
    
    Zengui_tmux_CheatSheet.pdf      Tmux quick-reference using the included
                                        tmux.conf !!!
_____________________________________________________________________________
INSTALL

    Copy in your home directory the included tmux.conf as follows:
    
        # cp tmux.conf ~/.tmux.conf    
        
    NOTE: The initial dot in the file is mandatory !
    
    If you want to use my preconfigured scripts you need to copy them also 
    with:
    
        # cp -a tmux.layouts ~/.tmux.layouts
        
    This scripts create new windows in a current session with some layouts
    and commands. You can load the scripts with:
    
        . Press keys        CTRL+A CTRL+L
        . In the prompt :   Type the name of one script, for example 'epages'
        
    Probably you need to edit the scripts to fit them in your environment.
    
    NOTE: A tmux script is simply a batch file with tmux commands.
    
_____________________________________________________________________________
HELP

    1.  You can use the included CheatSheet for a quick view for the basic
        commands
    
    2.  List the binding keys with CTRL+a ?
    
    3.  And of course, read the detailed man page !
    
    
    
