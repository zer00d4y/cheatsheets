# Stabilizing shell
    
    python3 -c 'import pty;pty.spawn("/bin/bash")'
    
CTRL + Z

    stty raw -echo; fg

    export TERM=xterm
