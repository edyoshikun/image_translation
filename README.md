# Exercise 4: Image translation

## Get the terminal ready.
If the `(base)` prefix is not present in front of the shell prompt, you need to initialize conda and restart the terminal:
```
conda init bash
```

## Fetch the readme and shell script from this repo.

```
git clone https://github.com/dlmbl/04_image_translation.git
cd 04_image_translation
```


## Setup data and environment.
Open the terminal and run the shell script that setups the data and the microDL repository. You are welcome to examine the script to understand the steps.
```
bash setup_data_environment.sh 
```

## activate the new conda environment.
```
conda activate micro_dl
```

## If working on a virtual desktop (e.g., NoMachine)

Launch jupyter lab from the terminal within your session:
```
jupyter lab
```

## If working on a terminal

Launch a jupyter lab server that you can connect from your browser: 

```
jupyter lab --ip=0.0.0.0 --port=8888 --no-browser
```

Then you can access your notebooks in your browser at:

```
http://<your server name>.compute.amazonaws.com:8888?<token generated by jupyter lab>
```

<your server name> is the host address you use to connect via ssh or nomachine, and *not the hostname displayed by jupyter lab in the terminal*. You do need to copy the token shown by the jupyter lab server in the terminal.

## Open the notebook
  
Open `microDL/notebooks/image_translation.ipynb`, and continue with the instructions in the notebook.



