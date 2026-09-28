Командой pstree-p посмотрела дерево оболочек(моя была дальше,чем 40,так что head -40 пришлось убрать)
![дерево](IMG_20260928_120721_985.jpg). 
PID  |   PPID     |      пользователь   |  команда |
3518  |  3465     |      user1    |        /usr/bin/bash |
3465  |  3457     |      user1    |        /usr/libexec/ptyxis-agent --socket-fd=3 --rlimit-nofile=1024 |
3457  |  2176     |      user1     |       /usr/bin/ptyxis --gapplication-service |
2176    |   1     |      user1   |         /usr/lib/systemd/systemd --user |
1     |     0      |     root    |         /usr/lib/systemd/systemd --switched-root --system --deserialize=55 rh |
