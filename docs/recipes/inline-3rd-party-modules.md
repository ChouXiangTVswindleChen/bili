# Inline 3rd-party modules

By default Bili inlines all 3rd-party modules in `umd` and `iife` format into your bundle, however you can use [`inline`](/api#inline) option to toggle this.

```bash
# Don't inline modules in UMD format
bili --format umd --no-inline
```
