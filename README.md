# Custom Terminal 🖥️ Guide 📜
    
## Introduction
     
This repository is mainly intended to be used as a safehouse (for now) for my terminal customizations and settings.<br> 
If you follow the instructions laid down here, you can change your terminal, that may look like this 👇
     
![alt text](Images/terminal-before-customization.png)
    
Into something that looks like this 👇
    
![alt text](Images/terminal-after-customization.png)
     
## Installation 
      
### Prerequisites
     
- **Nerd Fonts** : You can download these fonts from [here](https://www.nerdfonts.com/font-downloads). I use the [JetBrains Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/JetBrainsMono.zip) for my terminal.
    
### STEP 01 : Install Starship
       
[Starship](https://starship.rs/) is a highly customizable, cross-shell prompt. It works with popular shells like Bash, Zsh, Fish, PowerShell, and others. It will help us in changing the looks of our terminal.
   
### Windows
Starship can be installed via `winget`, windows package manager by running the following command in the `Command Prompt`. It will not work if you do not have `winget` installed already.
    
```
winget install --id Starship.Starship
```
   
If the above command does not work then we have to download the MSI-installers from the [release section](https://github.com/starship/starship/releases/tag/v1.20.1) of Starship's Github repository. Make sure to download the correct installer based on your CPU's Instruction Set Architecture (ISA), if you have a `x86_64` system download the installer that may look like this 👇
     
>
> starship-x86_64-pc-windows-msvc.msi 
>

### Linux
   
To install Starship, run the following command in your terminal.
     
```
curl -sS https://starship.rs/install.sh | sh
```
### STEP 02 : Configure your Shell to use Starship prompt