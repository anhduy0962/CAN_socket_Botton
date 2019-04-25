g++ `pkg-config gtkmm-3.0 --cflags --libs` click.cpp lib.cpp -o click

sudo /bin/ip link set can0 up type can bitrate 500000
./click
