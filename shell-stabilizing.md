# Stabilizing shell
    
    python3 -c 'import pty;pty.spawn("/bin/bash")'
    
    export TERM=xterm

Ctrl+Z

    stty raw -echo; fg