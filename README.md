# Welcome to CoMUX: A combinatorial-coding-baseaed high-performance MUX for microfluidic biochips!
### Tnis repo is the open source tool correspond to paper published in ICCAD' 22:
https://dl.acm.org/doi/abs/10.1145/3508352.3549353

This might be the $\color{yellow}{SOTA}$ microfluidic MUX. Here is an example to show how powerful it is:
Using 6 independent controllers, the classic-coding-based MUX can only address up to $\color{yellow}{2^{6/2}=8}$ channels, while CoMUX can address up to $\color{yellow}{C^6_3=20}$ channels.
This difference can become larger as the number of controllers increases.

<img width="500" alt="image" src="https://github.com/syliang1999/CoMUX/assets/111522473/f4a6e5ad-8895-4d60-bb79-75a9fe42a153">

# *** This repo can do two things: ***
### 1. Providing an easy-to-use tool to synthesize suggested CoMUX designs of different scales;
### 2. Helping users know what pressure pattern shouuld be taken to address a specific channel in the CoMUX

# *** User Instructions ***
### Step 1: Download the CoMUX.exe, and double click it to start, a new command window will be open automatically. (It is suggested to turn off the antivirus software like McAfee before start the program, otherwise the program might get deleted by the antivirus software.)
### Step 2: Input the number of to-be-addressed control channels, and press ENTER. Here we input 10 as an example.
<img width="500" alt="image" src="https://github.com/syliang1999/CoMUX/assets/111522473/76d5b71d-3706-4bc1-b3bf-72fe6e0b604f">

### An extra window will show the synthesized CoMUX design for 3s, then it will automatically close. If you wish to take a closer look at the design, please refer to the figure named MUX_layout.png stored at the current directory.
<img width="500" alt="image" src="https://github.com/syliang1999/CoMUX/assets/111522473/0c290eee-6ad2-49ef-9987-be655f74ea2d">

### Step 3: Please be careful and spend some time read the descriptions in the command window.
<img width="500" alt="image" src="https://github.com/syliang1999/CoMUX/assets/111522473/e06cbf11-6737-491c-a781-406abbb2093d">

### Step 4: Input the serial number of the channel you wish to address, and press ENTER. The pressure pattern needed to be applied will be returned.
<img width="500" alt="image" src="https://github.com/syliang1999/CoMUX/assets/111522473/6193672d-932a-441b-85c1-8c28e2113a18">

### After usage, just input 'exit', and the program will be terminated.

### Please feel free to contact us if you meet any probelm during the usage, cheers!
