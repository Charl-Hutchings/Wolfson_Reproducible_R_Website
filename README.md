# Template for R course

- This repo and site was created following the steps from [Andreas Handel's post on building Github websites](https://www.andreashandel.com/posts/2021-01-11-simple-github-website/)
- Feel free to clone and use for your own courses and website!


# Quick start
- Fork this repo
- The files with extension `.yml` (also known as YAML, "Yet Another Markup Language") are the configuration files which we modify the site theme, layout etc.
- The two in this repo you will need to configure are the `_navbar.yml` and `_site.yml`
- Put your `.Rmd` files also in the main directory (as per the example in this repo) and modify and add your lessons here remembering to update the `.yml` files as you go
- When ready to build your site in the console use the `rmarkdown::render_site()` command in the main directory where your files are located
- Push to Github and this will trigger a website build

# All the details
See Andreas Handel's post https://www.andreashandel.com/posts/2021-01-11-simple-github-website

# Github pages settings
- To allow Github Pages to build your site go to Settings -> Pages and make sure "Main" and "Docs" are selected under the "Build and Deployment" menu.
- You can either use "Deploy from Branch" or "Github Actions" we will currently use "Deploy from Branch"

# Final result
Ta da! [https://charl-hutchings.github.io/Wolfson_Intro_R_Website](https://charl-hutchings.github.io/Wolfson_Intro_R_Website/)
