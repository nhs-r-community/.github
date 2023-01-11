# Setting up a personal README

Full details on setting up the repository can be found through the [GitHub help pages](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).

The badges that appear on the GitHub entry page are possible for anyone's GitHub, whether that's individual or organisational, and are a great way of highlighting key information that you wish to share about the repository. For NHS-R Community we've used badges which are either just text or show tallies (as can be seen for YouTube, Mastodon and Twitter).

These have all been coded using html and include alternative text as well as links to websites.

## Using HTML (and previewing it)

HTML uses tags and the README includes `<br>` for breaks, `<h2> Text here </h2>` for header 2 and `<p align "center"> Text here </p>` to centre the paragraphs. It is possible to set up the README and write it from GitHub, but it's also nice to clone it (if you have permissions on the repository) to RStudio as it is possible to preview changes through the IDE rather than needing to commit each change to view them.

## Badges

The NHS-R Community GitHub has a commented out area with the acknowledgement to the badges/shields:

```
<!--
<details>
  <summary><b> Acknowledgements </b></summary>
  
https://shields.io/category/build 
</details> 

-->
```

Note, for badges that need links to the sites to reflect tallies you will need IDs for those sites. 

## Two READMEs

This is the README for the repository but the README that gets published on the front page can be found in the folder `profile/README.md`. 
