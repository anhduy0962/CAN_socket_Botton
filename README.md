sudo apt-get install libmysqlcppconn-dev
sudo apt-get install libgtkmm-3.0-dev
 sudo apt-get install libgtkmm-3.0
 
g++ `pkg-config gtkmm-3.0 --cflags --libs` click.cpp lib.cpp -o click

Client side:
sudo /bin/ip link set can0 up type can bitrate 500000
./click

Server side:
./candump can0
