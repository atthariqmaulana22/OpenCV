# OpenCV

sudo apt install -y build-essential libssl-dev zlib1g-dev libncurses5-dev \
libncursesw5-dev libreadline-dev libsqlite3-dev libgdbm-dev libdb5.3-dev \
libbz2-dev libexpat1-dev liblzma-dev tk-dev libffi-dev

wget https://www.python.org/ftp/python/3.11.4/Python-3.11.4.tgz
tar -xf Python-3.11.4.tgz
cd Python-3.11.4

./configure --enable-optimizations
make -j$(nproc)

sudo update-alternatives --install /usr/bin/python3 python3 /usr/local/bin/python3.11 1


python3.11 --version


sudo apt install -y build-essential cmake pkg-config libjpeg-dev libtiff5-dev libpng-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev libfontconfig1-dev libcairo2-dev libgdk-pixbuf2.0-dev libpango1.0-dev libgtk2.0-dev libgtk-3-dev libatlas-base-dev gfortran libhdf5-dev libhdf5-serial-dev libhdf5-103 libqt5gui5 libqt5webkit5 libqt5test5 python3-pyqt5 python3-dev
