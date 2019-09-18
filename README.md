# Overview
The purpose of this repo is to provide you with easy tools for auditing the security of your Ruby / Rails project.

It uses [Brakeman](https://brakemanscanner.org/) and [bundler-audit](https://github.com/rubysec/bundler-audit) to accomplish this.

# Setup
From your project root, copy the files in this repo into `ruby-audit-scripts`:
```
git clone --depth=1 git@github.com:atlantistechnology/ruby-audit-scripts.git
```

Optionally, remove git-related files and configuration:
```
rm -rf ruby-audit-scripts/.git  # Optionally remove git data
```

# Usage
Just run the scripts!
```
ruby-audit-scripts/brakeman
ruby-audit-scripts/bundler-audit
```

# License
MIT License. Copyright 2009-2019 [Atlantis Technology](https://www.atlantistech.com/).