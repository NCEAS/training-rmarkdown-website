# Tutorial on how to create a website using R Markdown

### To begin working on a website:
- Go to File -> New Project -> New Directory -> Simple R Markdown Website and then fill in the following boxes 
- As you can see, three files are created for you: _site.yml, about.Rmd, and index.Rmd
  - _site.yml: configuration file; Required file for this
  - index.Rmd: Rmd file containing all of the information on the home page; Required file for this
  - about.Rmd: Rmd file containing any information about website or purpose
- To build the website, go to the Build Pane on RStudio and press "Build Website" OR you can set your working directory to the folder you are working on and then use the function rmarkdown::render_site()

If you'd like to render Rmd files into a docs folder, you can add "output_dir: 'docs'" underneath the name of your website.



### To add additional pages to website:
- In the 
