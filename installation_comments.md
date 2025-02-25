### Basilisk instllation comments

Manually changing the bashrc file

Step1: Go to src folder of basilisk (*basilsik/src*)

step 2: Open the bashrc file
```bash
nano ~/.bashrc
```

step 3: Type the following commands
```bash
export BASILISK=$PWD
export PATH=$PATH:$BASILISK
```

step 4: Save the file and exit

step 5: Source the bashrc file
```bash
source ~/.bashrc
```

Now the following command should work -
```bash
qcc --version
```