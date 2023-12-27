# Introducing Land SE Python

Land executor is a project which is entirely coded in python and is under Land LLC directives.

Land Executor lets you inject any code into any virtual machine using any executor.

You can join out discord at : https://discord.com/invite/HpHCsnnj2T

Download at :
[ SOON ]


# Manual installation 🔌

To install Land SE manually you first have to install python on your compunter and install the following packages :

```py
pip install -r requirements.txt
```
Then, run the main.py file content.

When the GUI show up, press on attach and go to your virtual machine to execute this : ( Will work on hydrogen etc.. )
```lua
getkey()

getgenv().key = "land0f0cdbf266e29d3adfae9da32279ee0492ff520340580fb6da99057085b92c5a"

loadstring(game:HttpGet("https://raw.githubusercontent.com/Sponsoparnordvpn/VMInjector/main/init_executor.txt",true))()
```

You need to pass a 1 checkpoint linkvertise key system, and once it's done, put your key on getgenv().key.

The key passed, multiples warns / prints should appear : Congratulations, you did it !

Now enter your code in the code editor and press execute !!

Note : If it doesnt work try running it on a code IDE or just wait for Land LLC to release their c++ executor.
