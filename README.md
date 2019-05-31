# Tutorial on how to create a website using R Markdown

### To begin working on a website:
- Go to File -> New Project -> New Directory -> Simple R Markdown Website and then fill in the following boxes 
- As you can see, three files are created for you: _site.yml, about.Rmd, and index.Rmd
  - _site.yml: configuration file; Required file for this
  - index.Rmd: Rmd file containing all of the information on the home page; Required file for this
  - about.Rmd: Rmd file containing any information about website or purpose
- To build the website, go to the Build Pane on RStudio and press "Build Website" OR you can set your working directory to the folder you are working on and then use the function rmarkdown::render_site()

![image](https://media.github.nceas.ucsb.edu/user/152/files/11586800-83b0-11e9-9f8b-b542b0f59d16)

If you'd like to render Rmd files into a docs folder, you can add "output_dir: 'docs'" underneath the name of your website.

<img width="320" alt="screen shot 2019-05-31 at 2 15 02 pm" src="https://media.github.nceas.ucsb.edu/user/152/files/b40fe700-83ae-11e9-9e5f-4340b2478262">

### To add additional pages to website:
- Create an R Markdown file containing all of the information you want in that page

<img width="1377" alt="screen shot 2019-05-31 at 2 36 55 pm" src="https://media.github.nceas.ucsb.edu/user/152/files/49f94100-83b2-11e9-8b2e-43c9887b603f">

- In the _site.yml file, you have to add the following underneath the other pages:
   - text: the name of page 
   - href: the name of rendered html file (has to have the same name as R Markdown file)
   
<img width="445" alt="screen shot 2019-05-31 at 2 37 17 pm" src="https://media.github.nceas.ucsb.edu/user/152/files/5b424d80-83b2-11e9-8bfc-06e106696613">


