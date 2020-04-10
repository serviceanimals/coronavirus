<link rel="prerender" href="https://github.com/WAE/coronavirus">

## [WAE.virus.coronavirus](https://github.com/WAE/coronavirus)

##### -r--r--r-- [coronavirus.statistics.zsh](https://raw.githubusercontent.com/WAE/coronavirus/master/coronavirus.statistics.zsh)
##### -rwxrwxrwx [coronavirus.statistics.zsh](https://wae.github.io/coronavirus/coronavirus.statistics.zsh)

[This repository](https://github.com/WAE/coronavirus) is a submodule for [WAE.virus](https://github.com/WAE/virus).  In order to install it in its' proper place on a smartphone, tablet an TV, run [coronavirus.statistics.zsh](https://raw.githubusercontent.com/WAE/coronavirus/master/coronavirus.statistics.zsh) after downloading.  Alternatively, copy and paste the following into [Termux](https://github.com/termux):

```
   au git wget zsh || apt install git wget zsh # installs git wget and zsh

   mkdir -p ~/WAE/virus/coronavirus/ # creates directories

   cd ~/WAE/virus/

   git clone https://github.com/WAE/coronavirus # clones repository

   cd ~/WAE/virus/coronavirus

   coronavirus.statistics.zsh new-zealand uk # lists statistics
```
Run this command to see all available country names:
```
   coronavirus.statistics.zsh
```
[![Screenshot_20200408-062343.png](./docs/images/Screenshot_20200408-062343.png)](https://github.com/WAE/coronavirus/raw/master/docs/images/Screenshot_20200408-062343.png)

To configure default statistical output for China run this command in the root directory of this repository after cloning:
```
   echo china > .conf/COUNTRYSTAT
```
File [output/by.country.20200408.md](https://raw.githubusercontent.com/WAE/coronavirus/master/output/by.country.20200408.md) has example output to queries;  Example queries:
```
   coronavirus.statistics.zsh brazil france

   coronavirus.statistics.zsh canada japan

   coronavirus.statistics.zsh iceland mexico

   coronavirus.statistics.zsh italy norway

   coronavirus.statistics.zsh uk spain
```
File [output/by.new.mortality.20200409.md](https://raw.githubusercontent.com/WAE/coronavirus/master/output/by.new.mortality.20200409.md) was created by script [scripts/by.new.mortality.sh](https://raw.githubusercontent.com/WAE/coronavirus/master/scripts/by.new.mortality.sh) which lists countries by new mortality rate.

File [output/by.new.spread.20200409.md](https://raw.githubusercontent.com/WAE/coronavirus/master/output/by.new.spread.20200409.md) was created by script [scripts/by.new.spread.sh](https://raw.githubusercontent.com/WAE/coronavirus/master/scripts/by.new.spread.sh) which lists countries by new spread rate.

Recommended Internet searches during current viral pandemic:
```
   coronavirus meter

   "egg yolk" virus

   "egg yolk" virus site:.gov

   hydration virus

   hydration virus site:.gov
```
Bacteria, cancers, fungi and worms are not viruses.
<!--README.md EOF-->
