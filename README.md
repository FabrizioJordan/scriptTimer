# ⏱️ Script Timer

A simple timer for your scripts / commands

## ⚙️ Requirementes

Only you need to have:

Bash 4.0 or higher

And GNU 'date' command with nanoseconds support


## 📥 Installation

#### 🔧 Option 1: Clone with Git:

```
git clone https://github.com/FabrizioJordan/scriptTimer.git && cd ScriptTimer
```

```
chmod +x scriptTimer && sudo cp scriptTimer /usr/local/bin
```

#### 📦 Option 2: Manual installation from ZIP:

Go to the [GitHub repository](https://github.com/FabrizioJordan/scriptTimer)

Click the green “Code” button, then choose “Download ZIP”

Unzip the file on your system

Open a terminal in the folder where the script is located

Run the following commands:

```
chmod +x scriptTimer && sudo cp scriptTimer /usr/local/bin
```


After that, you can use scriptTimer from anywhere in your terminal.


### ✂️ Shorter command (optional)

If you want a shorter command, you can create a alias like ```xtime``` or ```sTimer```.

Or you can run this command (to create a Symlink):

```
sudo ln -s /usr/local/bin/scriptTimer /usr/local/bin/xtime
```


## 🧪 Usage


### 📘 How this script works?

It's easy. Just run the script and it will ask what command you want to time.

And finally the script will print the **total execution time**. 

### 💡 Examples of use

If you installed correctly the script, you just need to run the command.

```scriptTimer``` if you installed it normally or ```xtime``` if you use the shorter command.       

Then, just type the command you want to measure and hit enter.



## 🗑️ Uninstallation

During installation, the script is copied to /usr/local/bin. 

If you want to uninstall it, follow these steps:

To remove the script:

```
find /home/ -type f -name "scriptTimer" -exec rm {} \; && sudo find /usr/ -type f -name "scriptTimer" -exec rm {} \;
```

If you renamed the script during installation (e.g., to xtime):

```
find /home/ -type f -name "xtime" -exec rm {} \; && sudo find /usr/ -type f -name "xtime" -exec rm {} \;
```


