<h1 align="center">
  <br>
  WIFI-Brute-Force V1
  </br>
  </h1>
 <h1 align="center">
  <br>
  <a href="https://github.com/BrahimJarrar/"><img src="screenshot/screen.PNG" alt="VulnX"></a>
  </br>
</h1>

### _🕷️ Available command line options_
[`CopyRight`](https://github.com/BrahimJarrar/)

    usage: vulnx [options]
      -h , --help           show this help message and exit
      -s , --ssid           SSID WIFI Target
      -w , --wordlist       list of passwords
      -t , --threads        number of threads #Comming soon
      -v , --version        version

-------------------------------------

### How to use it in your Mac ?  
This project can run well on Windows and Linux. 
Because the dependent module pywifi support for Windows and Linux but not Mac,   
here is the way to use WIFI-Brute-Force in Mac.  
#### Step 1. install anaconda
Go https://www.anaconda.com/distribution/ to download anaconda and install it.  

#### Step 2. Use conda to install pywifi for mac
macos_dev branch is a pywifi project for Mac with python 3.5
pyobjc is dependent module for mac pywifi module

$ conda create -n wifi-brute-force python=3.5  
$ conda activate wifi-brute-force    
$ git clone -b macos_dev https://github.com/awkman/pywifi.git  
$ cd pywifi  
$ pip install pyobjc   
$ pip install .  

Now pywifi module for Mac is ready in conda environment, named wifi-brute-force  
You can enjoy WIFI-Brute-Force.  

