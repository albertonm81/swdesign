Installation notes

    sudo apt-get install git
    git clone https://github.com/tombaker/swdesign.git
    cd swdesign
    ipython notebook --ip=192.168.56.100

    Then go to browser: http://192.168.56.100:8888/

    Maybe use %rehashx to make !sparql into a native command??

Needed for running "ipython nbconvert"
    sudo apt-get install python-pip 
    pip install pygments           
    sudo apt-get install pandoc   

