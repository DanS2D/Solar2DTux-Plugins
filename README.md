List of Solar2D* plugins ported to Linux. Simply add the relevant entries to your `build.settings` file.

#### UTF-8
[Documentation](https://docs.coronalabs.com/plugin/utf8/index.html)

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
[Documentation](https://dannyglover.github.io/Solar2D-TinyFileDialogs-Plugin/)

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

#### Zip

[Documentation](https://docs.coronalabs.com/plugin/zip/index.html)

```  
settings =
{
    plugins =
    {
        ["plugin.tinyFileDialogs"] =
        {
            publisherId = "com.solar2d",
            supportedPlatforms = {
                ["linux-sim"] = {url = "https://github.com/DannyGlover/Solar2DTux-Plugins/raw/master/zip/data.tgz"},
            }
        },
    },
}  
```

#### Bit

[Documentation](https://docs.coronalabs.com/plugin/bit/index.html)

```  
settings =
{
    plugins =
    {
        ["plugin.bit"] =
        {
            publisherId = "com.solar2d",
            supportedPlatforms = {
                ["linux-sim"] = {url = "https://github.com/DannyGlover/Solar2DTux-Plugins/raw/master/bit/data.tgz"},
            }
        },
    },
}  