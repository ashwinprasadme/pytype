# Installing

    sudo apt install build-essential python3-dev libpython3-dev -y
    sudo apt install cmake bison flex -y
    
    git clone --recurse-submodules git@github.com:ashwinprasadme/pytype.git
    
    cd pytype
    pip3 install -e .

# Running

    pytype example-base.py