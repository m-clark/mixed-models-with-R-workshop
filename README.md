Mixed Models with R Workshop

This is the companion slides, data, and RStudio project for a workshop whose basis is the document: [Mixed Models with R](https://m-clark.github.io/mixed-models-with-R/). A previous version can be found [here](https://github.com/m-clark/mixed-models-with-r-workshop-2019), though this will be the primary workshop repo moving forward.  Once the workshop is conducted, the slides can be seen [here](https://m-clark.github.io/mixed-models-with-R-workshop/).


For the workshop, run the following in your R session to get the notes and materials for the workshop.  If you want, change the `destdir` to save the project in a specific place (not necessary, should default to desktop).  It will open the RStudio project for you, after which you can close the one you have open now.


```r
install.packages('usethis') # if you don't already have it

usethis::use_course(
  'https://github.com/m-clark/mixed-models-with-R-workshop/raw/main/mem_workshop.zip', 
  destdir = NULL
)
```

If you have issues, just download that zip file (click or paste the link above into your browser), unzip it to a location of your choosing, then:

- Click on the blue .Rproj icon inside

OR

- With RStudio - File/Open Project - Navigate to the folder - Open


With your RStudio project set up, you may read the accompanying `ReadMe.md`, then open `starter.Rmd` and go through it.
