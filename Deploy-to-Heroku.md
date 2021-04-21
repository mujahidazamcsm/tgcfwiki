Heroku is a cloud platform that lets companies build, deliver, monitor, and scale apps, it is one of the fastest ways to go from idea to URL, bypassing all those infrastructure headaches.

You can deploy `tgcf` to Heroku very easily. But there are some limitations currently. Heroku has an ephemeral file system. Thus you cant store your files here. `tgcf.config.yml` can't be created here. Instead, you can use an environment variable named `TGCF_CONFIG` to store the contents of the configuration file.

More information to be added soon...