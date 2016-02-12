## Go to Top plugin for Shaarli

A plugin for Shaarli (community fork) who add a "Go to top" button

### Installation/configuration
Clone this repository inside your `plugins/` directory, or download the archive and unpack it there.  
The directory structure should look like:

```
└── tpl
    └── plugins
        └── gototop
            ├── README.md
            ├── gototop.php
            ├── gototop.html
            ├── gototop.css
            ├── scroll2Top.js
            └── top.php
```

To enable the plugin, add `'gototop'` to your list of enabled plugins in `data/config.php` (`PLUGINS` parameter)
. This should look like:

```
$GLOBALS['config']['PLUGINS'] = ('gototop');
```
