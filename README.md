# Install Tor Browser

    echo deb https://deb.torproject.org/torproject.org stretch main | sudo tee -a /etc/apt/sources.list && echo deb-src https://deb.torproject.org/torproject.org stretch main | sudo tee -a /etc/apt/sources.list && curl https://deb.torproject.org/torproject.org/A3C4F0F979CAA22CDBA8F512EE8CBC9E886DDD89.asc | gpg --import && gpg --export A3C4F0F979CAA22CDBA8F512EE8CBC9E886DDD89 | apt-key add - && apt update && apt install tor deb.torproject.org-keyring torbrowser-launcher onioncircuits apt-transport-tor -y && neofetch


# Download Tor Browser

https://github.com/TheTorProject/gettorbrowser
