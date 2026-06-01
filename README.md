nohup ~/dufs /workspaces/codespace-storage -p 6666 --allow-all > ~/dufs.log 2>&1 &

ps aux | grep dufs


#for changing the file

nano ~/start-cloud-drive.sh


kill it

fuser -k 6666/tcp



























#for newbies do



wget https://github.com/sigoden/dufs/releases/download/v0.43.0/dufs-v0.43.0-x86_64-unknown-linux-musl.tar.gz
tar -xvf dufs-*-x86_64-unknown-linux-musl.tar.gz
mv dufs ~/dufs
chmod +x ~/dufs