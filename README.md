# byronfor25.com mirror

byronfor25.com is the secondary address for Byron Sigcho-Lopez's 25th Ward
campaign site. The main address is https://sigchofor25.com, built from the
`BSL-for-Congress` repo.

This repo holds no site content. `.github/workflows/mirror-site.yml` checks the
main repo every 15 minutes and, when it has a new commit, builds the same site
and deploys the copy to byronfor25.com. Every page on the copy names
sigchofor25.com as its canonical address.

`.mirrored-sha` records the last main-repo commit that was deployed here.
To force a rebuild, run the workflow by hand from the Actions tab.
