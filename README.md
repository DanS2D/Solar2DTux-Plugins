List of Solar2D* plugins ported to Linux. Simply add the relevant entries to your `build.settings` file.

#### UTF-8
Documentation: [Here](https://docs.coronalabs.com/plugin/utf8/index.html)

```
settings =
{
    plugins =
    {
        ["plugin.utf8"] =
        {
            publisherId = "com.solar2d",
            supportedPlatforms = {
                ["linux-sim"] = {url = "https://github.com/DannyGlover/Solar2DTux-Plugins/raw/master/utf8/data.tgz"},
            }
        },
    },
}
```

#### Tiny File Dialogs
Documentation: [Here](https://dannyglover.github.io/Solar2D-TinyFileDialogs-Plugin/)

```  
settings =
{
    plugins =
    {
        ["plugin.tinyFileDialogs"] =
        {
            publisherId = "com.revolt64",
            supportedPlatforms = {
                ["linux-sim"] = {url = "https://github.com/DannyGlover/Solar2DTux-Plugins/raw/master/tinyFileDialogs/data.tgz"},
            }
        },
    },
}  
```