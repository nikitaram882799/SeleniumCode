

Steps to Install Selenium

Login to Ubuntu 20.04

1) Execute sudo su - to login as root

2) Install below command to install packages

apt install default-jdk maven unzip

3) Install Chrome Browser on Linux

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo apt install ./google-chrome*.deb

4) Chrome webdriver to execute requests on Chrome browser

wget https://chromedriver.storage.googleapis.com/114.0.5735.90/chromedriver_linux64.zip

unzip chromedriver_linux64.zip

cp chromedriver-linux64/chromedriver /opt

https://chromedriver.chromium.org/downloads
