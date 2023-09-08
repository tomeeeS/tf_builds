# tf_builds
tensorflow builds

## Git LFS

```
# install git lfs (for the tensorflow wheel)
echo 'F2 - install git lfs'
sudo mkdir -p /tmp/lfs
cd /tmp/lfs || exit
wget https://github.com/git-lfs/git-lfs/releases/download/v3.4.0/git-lfs-linux-amd64-v3.4.0.tar.gz
tar -xf git-lfs-linux-amd64-v3.4.0.tar.gz
cd git-lfs-3.4.0 || exit
chmod 755 install.sh
./install.sh
git lfs install
cd /opt/rnd/flex_forecasting_server || exit
```
