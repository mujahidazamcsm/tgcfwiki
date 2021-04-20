The application `tgcf` is configured using a simple `YAML` file. If you are new to the `YAML` syntax, don't worry, it's easy, and you will learn it.



Below is an example configuration. Don't copy-paste this. Understand what each part does.

```yaml
forwards:
  - source: -1001412118156
    dest: [-1001461332656,-1001457230530]


show_forwarded_from: false

plugins:
  filter:
    text:
      blacklist: ["nope"]
  replace:
    text:
      god: devil
      tokyo: delhi
      
```

More explanation coming soon...