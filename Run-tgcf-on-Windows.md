Windows is a mess! In Linux or Mac, a terminal and python are generally pre-installed. But that's not the case with windows.

Here goes the complete guide to set up and use `tgcf` on a Windows machine.

## Pre-requisites

1. Open Microsoft Store

   ![image](https://user-images.githubusercontent.com/66209958/115837680-7a2eaa80-a436-11eb-9cca-11e12694e8b3.png)

2. Install [Powershell]() , [Windows Terminal](), and Python 3.9


   ![image](https://user-images.githubusercontent.com/66209958/115838965-d0e8b400-a437-11eb-818a-652951ae44ee.png)

   ![image](https://user-images.githubusercontent.com/66209958/115839446-49e80b80-a438-11eb-9149-b93d6218e0dc.png)
    
   ![image](https://user-images.githubusercontent.com/66209958/115839540-608e6280-a438-11eb-91e6-9285cc6301ee.png)

3. By default windows has Notepad. Its a   horrible text editor. Windows file explorer is also shitty. It appends `.txt` to every text file. For a better experience, Install VS Code from [code.visualstudio.com](https://code.visualstudio.com/) for easy editing of text files.
When you will be writing the `tgcf.config.yml` VS code will automatically provide syntax highlighting and type checking.
   ![Screenshot (7)](https://user-images.githubusercontent.com/66209958/115840953-e4951a00-a439-11eb-9db4-b87733e2dd98.png)

## Install tgcf

 Open Powershell in Windows Terminal and run pip install tgcf

   ![image](https://user-images.githubusercontent.com/66209958/115841408-6127f880-a43a-11eb-92fd-215ab3a4c8aa.png)


## Configure and Run

1. You should create a new folder to store `tgcf` configuration files. Every time you run `tgcf` you should run from inside this folder. 

2. Open the folder with VS Code and create the files `.env` and `config.tgcf.yml`. 
You will be required to login to your Telegram account only for the first time. The session files will be stored in this folder. Don't delete them, and keep them secret.

, go inside it, create .env and tgcf.config.yml, run tgcf



