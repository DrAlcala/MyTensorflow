# MyTensorflow
------------------------
Using Ubuntu 18.04LTS on Windows Subsystem for Linux(WSL).
1. Installed anaconda3 
   1. https://www.anaconda.com/download/#linux
   2. per instructions, add conda to .bashrc. In terminal edit file with command.  
        \>>nano ~/.bachrc
   3. At the every bottom of the file add.
        \>>source /home/jalcala6/anaconda3/etc/profile.d/conda.sh
   4. Press Ctrl X then Y to save the file. Type the following command in the terminal to activate the .bashrc file.
        \>>source ~/.bashrc           
2. Created env with python 3.5. Tensorflow supports python 3.5 at this time.
   1. \>>conda create --name tensorflow_env python=3.5
   2. To enter the ENV use the following command. Then install tensorflow. The Windows Subsystem for Lunix(WSL) only supports CPU tensorflow installation.
      1. \>>conda activate tensorflow_env
      2. \>>pip install tensorflow
3. The following commands will install dependencies needed to use edit it and write tensorflow code.
   1. \>>conda install numpy
   2. \>>pip install pandas
   3. \>>pip install python-utils
   4. \>>conda install scikit-learn
   5. \>>conda install seaborn
      
    
