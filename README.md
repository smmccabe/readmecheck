# readmecheck

Used to check drupal modules for standard compliant readme files. It can be run on a site to check all modules or modules from a specific folder, like "custom".

## Installation

```
wget https://raw.githubusercontent.com/smmccabe/readmecheck/master/readmecheck
chmod +x readmecheck
sudo mv readmecheck /usr/local/bin/readmecheck
```

## Usage

check all modules on a drupal 7 site
```
readmecheck sites/all/modules
```

check a specific module
```
readmecheck commerce_shipping
```

check your custom module folder on drupal 8
```
readmecheck modules/custom
```
