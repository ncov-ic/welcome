## Welcome to the Imperial ncov Team

### Communications

Please make sure that you have access to the ncov team on Microsoft Teams.  If not, please email Rich, Amy, Katy and/or Natsuko to be added.  Your experience with Teams will be better if you download the standalone-application, which is available on all platforms.

There is an email list nCoV-2019 - you will know if you are on it.  If not please email Katy, Natsuko and/or Amy to be added.

There is a zoom call every weekday, and a summary email every weeknight.

### Shared source code

All our source code is on GitHub within the [ncov-ic](https://github.com/ncov-ic) organisation.  If you are not a member of this organisation, please contact Rich, Natsuko or Amy.  You're not a member if you can't read the [ncov-outputs](https://github.com/ncov-ic/ncov-outputs) repo.

In addition, you must also be a member of the [mrc-ide](https://github.com/mrc-ide/) organisation.  If you're not sure ask Rich or Wes.

**Please do not use private repositories on your personal github accounts**

Anything that is going to feed into the reporting framework needs to be implemented in the [ncov-outputs](https://github.com/ncov-ic/ncov-outputs) repo - see instructions within.

### Software

There is software to install, particularly for using orderly.  To get started, run

```r
# install.packages("drat") # (install this if you don't have it already)
drat:::add("ncov-ic")
install.packages(c("orderly", "vaultr", "orderlyweb"))
```

You need to get git installed and set up.  [These installation instructions](https://github.com/richfitz/git-intro/blob/master/installation.md) work for most people.  See also [Happy Git and GitHub for the useR](https://happygitwithr.com/)
