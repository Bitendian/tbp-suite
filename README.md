# TBP Suite

This is just a *meta-package*, grouping TBP core and other TBP libraries.

Those libraries use to be in most TBP projects, so may be do you want to add
this *meta-package* instead of picking everyone of those libraries one-by-one.

## Suite contents

- TBP core
- TBP JWT support
- TBP static i18n management
- TBP deploy tools
- TBP HTML helpers

## Installation

Just add the suite repository to your project composer.json, and ```tbp-suite```
as project requirement.

For example:
```
    "repositories": [
        { "type": "vcs", "url": "git@github.com:Bitendian/tbp-suite.git" }
    ],
    "require": {
        "bitendian/tbp-suite": "^0.9"
    }

```