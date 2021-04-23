## Default behavior 

When you run `tgcf` for the first time, it will interactively prompt you to enter your phone number or bot token. A session file will be generated and saved in the folder from which you ran `tgcf`.

When you will run `tgcf` again, from the same folder, you will not be required to log in.

## Generate Session String

Do you want to deploy `tgcf` to a cloud platform but during the deployment process, you don't have an interactive shell?

For that, you may generate a session string by running `tg-login` in an interactive shell, and then copy the value of the session string printed to the console. This value should be put inside the environment variable `SESSION_STRING`.

- Open your terminal in Mac/Windows/Linux/Android
- Make sure you have `python` installed.
  If you don't have python:
    - for Linux/Mac, its generally already installed.
    - for windows install python 3.8 or above from the Microsoft store
    - for android (termux) run `pkg install python`

- Install `tg-login` by running `pip install tg-login`
- Run `tg-login`
- It will prompt you to enter your details, and then print your session string on the screen.
- Copy the session string, and never share it with anyone.


