# Potential Projects

Here are a number of potential research projects I'm interested in working on.

## Combine IFU data cubes with archival aperture photometry

https://github.com/yoachim/IFU_Aperture_Phot

Given the wealth of archival imaging out there, we need stellar population fitting software that can incorporate both spectra and photometry. There are a huge number of codes that fit spectra, and a bunch that fit SEDs (see http://www.sedfitting.org/SED08/Fitting.html), but I still haven't found anything that does both. UPDATE: Nice new code that can fit spectra and photometry: [SPARTAN](https://bitbucket.org/spartan_project/spartan/wiki/Communication)


## PSF effects on measuring thick disk flux

This paper http://adsabs.harvard.edu/abs/2015A%26A...577A.106S basically makes the claim that my thesis work is junk because I didn't take into account how light diffracts as it is imaged by the telescope.  

## LSB co-added images in LSST

It would be nice to have a procedure in the LSST framework for generating co-added images that is optimized for low surface brightness work. Could be a paper summarizing the general algorithm, then an implantation in the stack.

## Are GLSB cores normal elliptical galaxies?

XXX-touch base with Denise to see what's going on here.
follow-up based on this paper: https://github.com/yoachim/glsbPaper

High spatial resolution IFU observations on these objects would be great.

## VIRUS-P of UGC1382 

This is another good target for deep IFU observations

## Telescope Scheduling

I'd like to modify astroplan to estimate signal-to-noise since that is the thing observers tend to want to optimize. 


## Stellar metallicities with LSST + narrow band filters

Take a bunch of stellar spectra, figure out how well LSST will be able to recover stellar metallicity. What if we add a narrow-band filter? https://github.com/lsst-sims/sims_narrowband_stellarZ

## Astronomer Employment via publication records

damn, I need to finish this:
https://github.com/yoachim/AstroHireNetwork


## Gemini South Archive of Stellar Spectra

Use the Gemini South data archive to look at how the sky background and atmospheric parameters vary with time. Talk from SPIE made it sound like they were already doing similar things. (talk was by Katherine Roth (Gemini) of work by Aam Smith (Gemini)).

## Structure in Outer Galaxy Disks

In this paper (http://adsabs.harvard.edu/abs/2012ApJ...752...97Y), we looked at the star formation histories in the outskirts of 12 galaxies.  Given new simulations, we'd like to see if there are spiral arms or other excited modes in the faint outer parts of these galaxies.  If we can't find archival data, this would be a fun observing project to use APO for. 

## Making better plots

I would like to make a utility function that makes it easy to generate publication-ready and slide-ready and web-ready images all at the same time:  https://github.com/yoachim/matplotlib_pubplots

## Stellar metallicities with LSST and narrow band imaging

If we were to add a narrow band filter to LSST, where should we put it to optimize how well we can recover stellar metallicities?  
