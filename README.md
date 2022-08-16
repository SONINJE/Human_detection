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
