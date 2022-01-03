# Potential Projects

Here are a number of potential research projects I'm interested in working on.


## Fitting All Sky Camera WCS

Most observatories these days have all-sky fishey cameras to monitor the weather. It should be possible to automate fitting the WCS solution of these sorts of cameras, then making a pipeline to automate detection of clouds and things.  

Initial notebook playing around with it here:  https://github.com/yoachim/20_Scratch/blob/master/all_sky_example/example_all_sky.ipynb

This would be a great project to fold into the astropy WCS filtting procedure, or make an astropy affiliated package.

## Proper uncertainties on star formation histories

I have some galaxy spectra I'd like to fit star formation histories to. I think this package is what I'm looking for, just need to figure out how to run it:  https://dfm.io/python-fsps/current/

or maybe this one:  https://prospect.readthedocs.io/en/latest/

Or maybe this one:  https://bagpipes.readthedocs.io/en/latest/


## LSB co-added images in LSST

It would be nice to have a procedure in the LSST framework for generating co-added images that is optimized for low surface brightness work. Could be a paper summarizing the general algorithm, then an implantation in the stack.


## VIRUS-P of UGC1382 

This is another good target for deep IFU observations

## Telescope Scheduling

I'd like to modify astroplan to estimate signal-to-noise since that is the thing observers tend to want to optimize. 


## Stellar metallicities with LSST + narrow band filters

Take a bunch of stellar spectra, figure out how well LSST will be able to recover stellar metallicity. What if we add a narrow-band filter? https://github.com/lsst-sims/sims_narrowband_stellarZ

There was some work started on this, I'm not sure the paper ever got submitted. Looks like there was some work here:  https://www.overleaf.com/project/5d675af7d9c3da5e667b0415

and another repo here:  https://github.com/yoachim/LSST_narrowband

## Star Galaxy Separation with IR

Similar to the above, I want to know how well we could do star galaxy separation in LSST data if we had IR observations as well. In theory, galaxies should be bright in the IR while stars get fainter.

## Astronomer Employment via publication records

damn, I need to finish this:
https://github.com/yoachim/AstroHireNetwork

## A meta science project

Could look at how HST proposals perform as a function of oversubscription (and other things, time alloted, etc)

