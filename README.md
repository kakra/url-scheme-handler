# Installation

1. Install ruby
2. Copy 'url-scheme-handler' to a location on PATH (e.g. '/usr/local/bin')
3. Run `url-scheme-handler --install SCHEME` (see below)
4. Now install, e.g., [BetterErrors](https://github.com/charliesome/better_errors) in Rails and configure it 


# Supported Schemes

This script currently only supports sublime3 through the `subl://` scheme and
expects 'subl3' on your path. It should be easy to support other editors and
I'm happy to merge pull requests and patches.

To install support for, e.g. Sublime3, run:

```bash
url-scheme-handler --install subl
```


# Disclaimer

This application is provided as-is. Feel free to use at your own risk.

Original author: "Kai Krakow" <hurikhan77+github@gmail.com>
