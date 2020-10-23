List of Solar2D* plugins ported to Linux. Simply add the relevant entries to your `build.settings` file.

#### UTF-8

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