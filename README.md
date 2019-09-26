# CompPhysNumpyExamples

**IMPORTANT: READ THESE INSTRUCTIONS.**

Here you will exercise a few advanced python skills, using `jupyter` notebooks: 

- Problem 1: Array programming and selections. 
- Problem 2: Array programming operations and plotting. 
- Problem 3 (grad students only): using C++ and python with SWIG


## Setup the software 
To perform Problem 3, you will need to have this package **in a parallel directory** to the standard CompPhys package. 


Assuming your folder where you work is called `/home/yourusername/working` 
(and has the contents `results` and `CompPhys`): 

**On your host OS** (that is, your laptop... not the docker image):
```
cd /home/yourusername/working/results            #<-- Put in YOUR path to YOUR results folder
git clone https://github.com/rappoccio/CompPhys.git
git clone https://github.com/rappoccio/CompPhysNumpyExamples.git
```

For your assignment **replace the last line** with your assignment 5 github area. Here is mine (yours is different): 
```
git clone https://github.com/ubsuny/technical-assignment-5-rappoccio.git
```

Then, you go to your "CompPhys" folder to execute `jupyter` from the `docker` image. 
```
cd /home/yourusername/working/CompPhys
./runDocker.sh srappoccio/compphys:latest 0
```

## Perform the exercises. 

Then go to [your browser window](127.0.0.1:8888) and you should have access to the various problems. 


## Commit your code for the assignment

Go to your assignment directory (mine is below, yours will be different). 
```
cd /home/yourusername/working/results/technical-assignment-5-rappoccio
git add -u . 
git add (whatever other files you need)
git commit -m"I hope I passed"
git push origin master
```
