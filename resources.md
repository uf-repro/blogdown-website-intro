# Additional Resources / Readings

## Troubleshooting

Having build problems? You may need to update `{{blogdown}}` or `{{Hugo}}`

1. Install the latest version of blogdown.  
  ```
  install.packages("blogdown")
  ```
  
2. Use blogdown to install Hugo.  
  ```
  blogdown::install_hugo()
  ```
  
3. Open `.Rprofile` and set the hugo version to the version you just installed.
4. Session -> Restart R.
5. Update the `renv` snapshot.  
  ```
  renv::snapshot()
  ```
  
6. Test  
  ```
  blogdown::serve_site()
  ```
  
7. Commit and Push.

## Reference Documentation

* ["Hugo Apéro: A Hugo theme you'll want to hang out with"](https://hugo-apero-docs.netlify.app/)
  - Documentation Site for the Hugo Apéro theme.

* ["Introduction to renv"](https://rstudio.github.io/renv/articles/renv.html)
  - A starting guide for the `{{renv}}` package.

* ["blogdown: Creating Websites with R Markdown"](https://bookdown.org/yihui/blogdown/)
  - The book on `{{blogdown}}`

## Guides

* ["Managing Git(Hub) Credentials"](https://usethis.r-lib.org/articles/git-credentials.html)
  - Instructions to set up GitHub credentials for use with `{{usethis}}`

* ["Happy Git and GitHub for the useR"](https://happygitwithr.com/)
  - Detailed instructions and workflows for installing Git, connecting it with GitHub, and configuring RStudio to work with Git and GitHub

* ["Markdown Cheatsheet"](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  - A guide from Adam Pritchard on formatting of Markdown documents

* ["About GitHub Pages"](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites)
  - documentation on GitHub Pages; this link goes specifically to information about how the username and reponame are transformed into the URL

## Other

* ["Hugo Themes"](https://themes.gohugo.io/)
  - A collection of website themes that work with Hugo.
  
* ["Netlify"](https://bookdown.org/yihui/blogdown/netlify.html)
  - The Netlify section of the blogdown book, which discusses using Netlify to deploy your website.

