## Welcome to the Imperial ncov Team

### Communications

Please make sure that you have access to the ncov team on Microsoft Teams.  If not, please email Rich, Amy, Katy and/or Natsuko to be added.  Your experience with Teams will be better if you download the standalone-application, which is available on all platforms.

There is an email list nCoV-2019 - you will know if you are on it.  If not please email Katy, Natsuko and/or Amy to be added.
Please treat _everything_ shared via the mailing list as confidential.

There is a zoom call every weekday, and a summary email every weeknight.
For the zoom call, if you have any updates you would like to raise, please post it to the Teams channel #daily_updates.

### OneDrive
We are now working solely on OneDrive. Once you have accepted the Teams invite, this gives you automatic access to the 2019-nCoV onedrive folder. _Please treat everything on this as highly confidential_.

#### Access OneDrive
1) Accept the Teams email invite.
2) Go to: https://imperiallondon.sharepoint.com/sites/ncov
3) Make sure the "Following" star in the top right is selected.
4) Click on the waffle (top left by the Imperial logo) and select OneDrive
5) On the right hand side there is a "shared libraries" section. Select `ncov`.
6) Click on `2019-nCoV` folder.
7) Click "Sync".
8) This should prompt you to open OneDrive (recommend to download the desktop app) this will then sync this file to your computer in the same way as Dropbox does.

### Shared source code

All our source code is on GitHub within the [ncov-ic](https://github.com/ncov-ic) organisation.  If you are not a member of this organisation, please contact Rich, Natsuko, Katy or Amy **and include your github username**.  You're not a member if you can't read the [ncov-outputs](https://github.com/ncov-ic/ncov-outputs) repo.

If you do not know your github username, click the little icon on the top right of the [github landing page](https://github.com).

In addition, you must also be a member of the [mrc-ide](https://github.com/mrc-ide/) organisation.  If you're not sure ask Rich or Wes, again including your github username.

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
