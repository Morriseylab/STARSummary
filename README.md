# STARSummary

Website to view the results from STAR aligner and picard tools viz STAR summary statistics, markdups, library complexity summary and metrics form picard tools.

## Requirements
- R (version > 3.4)
- RStudio Server
- Shiny Server (if you need to host it online)

If you need help installing the above or getting started, refer to [this](https://deanattali.com/2015/05/09/setup-rstudio-shiny-server-digital-ocean/#install-r)

Run the script from [here](https://github.com/Morriseylab/scripts/blob/master/run_STAR_singlepass.pl)

### Adding your dataset

Add your data to the param.csv file and move it to the data directory. You can find an example dataset [here.](http://165.123.69.6/STARSumm/Exampledata.RData) Please note that the data directory must be in the same location as your server.R and ui.R files. The param.csv file should also be saved in the data directory as the RData files.
