The Termux app in Android offers you a full-blown Linux terminal.

![image](https://user-images.githubusercontent.com/66209958/115503616-559acd00-a294-11eb-8909-a27ff9a6efd6.png)

Hopefully, you have already read the README for a basic introduction to `tgcf`.

## Steps

1. Install [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en&gl=US) from Google Play Store.
2. Open termux and play around by running basic Linux commands like `clear`, `ls`, `pwd` etc.
3. Install `python`.
   ```shell
      pkg install python
   ```
4. Check if the proper version of `python` and `pip` got installed.
   ```shell
      python --version # should output above 3.9
      pip --version # should output above 20
    ```
5. Now install `tgcf` via `pip`, which is python's official package manager.
   ```shell
      pip install tgcf==0.1.17
    ```
6. Check if `tgcf` was installed correctly.
   ```shell
      tgcf --version # should output 0.1.17
      tgcf --help # will show you the CLI usage
   ```
7. Learn about 
   - [environment variables](https://github.com/aahnik/tgcf/wiki/Environment-Variables), 
   - [CLI usage](https://github.com/aahnik/tgcf/wiki/CLI-Usage) and 
   - how to [configure tgcf](https://github.com/aahnik/tgcf/wiki/How-to-configure-tgcf-%3F), 
   and then start using `tgcf`.

