The secret credentials like `API_ID` and `API_HASH` are stored as environment variables.

You can easily set environment variables for `tgcf` using a `.env` file in the directory from which `tgcf` is invoked.

```shell
API_ID=543213
API_HASH=uihfuiwruiw28490238huawfiuhf
# put your real values here
```

When you are deploying to a cloud platform, and you cant create files (Heroku or digital ocean apps), you can set environment variables using the GUI provided by the platforms. Please read platform-specific guides in the wiki for more details.

When you are deploying on a cloud platform, you can configure tgcf using environment variables. The contents of `tgcf.config.yml` can be put inside the environment variable called `TGCF_CONFIG`.