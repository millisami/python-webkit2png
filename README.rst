***This project is looking for a maintainer - Please contact me if you're interested***


Originally taken from the blog post by Roland Tapken at:
http://www.blogs.uni-osnabrueck.de/rotapken/2008/12/03/create-screenshots-of-a-web-page-using-python-and-qtwebkit/

---
On ubuntu you need to add following packages:

    sudo apt-get install python-qt4 libqt4-webkit python-pip
    sudo apt-get update
    sudo apt-get install python-qt4 libqt4-webkit python-pip xvfb

---
And then install it with:

    sudo pip install webkit2png

    wget https://raw.github.com/millisami/python-webkit2png/master/webkit2png.py
    
    xvfb-run --server-args="-screen 0, 640x480x24" python ./webkit2png.py -o /vagrant/test.png http://etxpress.com