# COVID-19-operational-forecast

I've been following James Annan's blogposts and tweets about the armchair epidemic modelling he's been doing. I don't really get the underlying model, so have decided to spend some time trying to understand it. I've forked this repository from the Rmd code supplied by @jdannan. That in turn is based off the version of [SEIR](https://www.idmod.org/docs/hiv/model-seir.html) model deployed by @thomasallanhouse in his [blogpost on herd immunity](https://personalpages.manchester.ac.uk/staff/thomas.house/blog/blog.html). @thomasallanhouse provided some python code at the bottom that post which I've popped in the understanding.ipynb

A basic SEIR model contains 4 population reserviors, which are _Susceptible, Exposed, Infectious, Recovered_ (hence the acronym) along with some flows between them.


## Original README.md text from @jdannan
### simple MCMC parameter estimation for forecasting COVID deaths (etc)

*Should run out of the box (once you've put the data file in the right place) to generate the forecast I
published on morning of 11 April based on data to 10 April. It's an Rmarkdown document that runs in
RStudio but I'm sure you can work out how to execute the code via your workflow of choice.*

*UK.worldometer.txt needs to go in a data subdirectory (or just change the path in the code of course).
It's basically cut and paste from the html on the UK worldometer page to create a trivial csv file.
Other data sources are available.*
