Heroku is a cloud platform that lets companies build, deliver, monitor, and scale apps, it is one of the fastest ways to go from idea to URL, bypassing all those infrastructure headaches.

You can deploy `tgcf` to Heroku very easily. 

## Limitations

- Heroku has an ephemeral file system. 
- Thus you cant store your files here. 
- `tgcf.config.yml` can't be created here. 
- Instead, you can use an environment variable named `TGCF_CONFIG` to store the contents of the configuration file.
- `tgcf` in past mode won't work properly in Heroku, as the environment variable TGCF_CONFIG can't be updated.

## Pros

- `tgcf` will work **perfectly fine** in `live` mode in Heroku.
- Heroku offers a great free tier of 450 hrs/mo

## One-click deploy

1. Click on this button. 

   <a href="https://heroku.com/deploy?template=https://github.com/aahnik/tgcf">   <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" width=155></a>

2. A Heroku page will open where you can set all the environment variables.

   
