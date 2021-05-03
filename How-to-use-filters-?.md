Filters allow you to selectively forward some messages while excluding others.

Currently, filters based on text whitelist and blacklist are available.

For an intro to configuration [read this](https://github.com/aahnik/tgcf/wiki/How-to-configure-tgcf-%3F) page.

To use text-based filtering, put the following in your configurations:

```yaml
plugins:
  filter:
    text:
      blacklist: ["nope","idiot"]
      whitelist: ["hello"]
```

You can add many words to the blacklist or whitelist. You may use either whitelist or blacklist or both.