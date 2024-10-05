## Estimating epidemic parameters from viral load data

One of my PhD projects was to see if viral load data collected from infected individuals during the beginning of an 
epidemic could be used to estimate the basic reproductive number. To do this, I assumed that
someone's viral load is a function of how long they have been infected, which is their age-of-infection, 
and the distribution of the ages-of-infection among the infected approaches a limit during the beginning of 
an epidemic. From this, we can derive the distribution of viral loads among the infected and create a 
maximum likelihood estimator. More details and code are provided in the [repository](https://github.com/briantreacy/epi_param_estimation_viral_loads).



