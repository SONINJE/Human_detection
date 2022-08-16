# Human_detection

gcc install
 -------------
      sudo apt update

      sudo apt install build-essential
---------------
cuda install
---------------
    wget https://developer.nvidia.com/compute/cuda/10.1/Prod/local_installers/cuda_10.1.105_418.39_linux.run

    sudo sh cuda_10.1.105_418.39_linux.run
    
    vi ~/.bashrc
        export PATH=/usr/local/cuda-10.1/bin${PATH:+:${PATH}}$
        export LD_LIBRARY_PATH=/usr/local/cud-10.1/lib64${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
--------------
gpu driver install
 -------------
      sudo apt-get install nvidia-driver-390

      sudo reboot    
 -------------
cudnn install
 -------------
      wget http://developer.download.nvidia.com/compute/redist/cudnn/v7.6.5/cudnn-10.1-linux-x64-v7.6.5.32.tgz

      sudo tar -xzvf cudnn-10.1-linux-x64-v7.6.5.32.tgz    
 -----------------     
anaconda install
 -------------
      curl -O https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
      
      bash Anaconda3-5.2.0-Linux-x86_64.sh
      
      source ~/.bashrc
      
      conda update conda
 ------------------     
python 3.8 install
 -------------
      sudo apt update
      
      sudo apt install software-properties-common
     
      sudo apt install python3.8

      python3.8 --version
 ----------------------
# conda Create a virtual environment
--------------------
     conda create –n tensorflow pip python=3.8

     conda activate tensorflow
 
     pip install tensorflow==2.3.1
