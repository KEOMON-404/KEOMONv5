#-----TERMUX SETUP-----#
pkg update && pkg upgrade
pkg install python
pkg install git
pkg install bs4
pkg install rich
pkg install requests
pkg install mechanize

#-----COMMAND-----#
rm -rf KEOMONv5
git clone https://github.com/KEOMON-404/KEOMONv5
cd KEOMONv5
python run py
