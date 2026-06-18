cp ./rclone /usr/bin/
chmod +x /usr/bin/rclone

usage:
rclone copy /mnt/src /mnt/dst -Pvv --transfers 32 --checkers 64 --links --create-empty-src-dirs

