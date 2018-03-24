Copy phison-VERSION (replcace VERSION with the version of said folder) to /usr/src

Install with:

sudo dkms add -m phison -v VERSION
sudo dkms build -m phison -v VERSION --all
sudo dkms install -m phison -v VERSION --all
