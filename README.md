# resharper cookbook

Used for installing JetBrains ReSharper 7.

# Requirements

Visual Studio is already installed

# Usage

Include the default recipe in your run list.

# Attributes

* `node['resharper']['version']` - Defaults ReSharper 7.1.3. If you change this you'll need to change product name and checksum.

# Recipes

default
-------
Installs ReSharper 7.1.3.

# Author

Author:: Shawn Neal (<sneal@daptiv.com>)