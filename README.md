# ASTR 19 Final Project

### Contributors
Ian Richardson

The final projects involve developing programs to analyze and assess the statistical significance of events in scientific data relative to a model. Detailed instructions will be provided on Canvas, and students should expect to begin working on the project starting in the 7th week of the course.

Use the following link to make a copy of the Google Document you will use to submit your final (remember to change the sharing permissions):

Final Project Google Doc (Links to an external site.)

As you create your final project in a Jupyter notebook, you will upload your notebook to GitHub and provide the URL link to the notebook in the Google Doc. You'll submit the URL to the Google Doc as the submission to the assignment (just like with the Code Journals).

 
### Final Project Instructions

Steps 1-2 below are preparatory, while Steps 3-5 should appear in the Jupyter notebook uploaded to GitHub.

1) Get astropy and install it on your system (pip install astropy).

2) Get sep and install it on your system (pip install sep).

3) Follow the tutorial found at https://sep.readthedocs.io/en/v1.0.x/tutorial.html, but use the astropy fits routines instead of fitsio. Create a notebook that performs the tutorial and comment it using Markdown to explain what it’s doing. Note that the fits image used in the tutorial can be acquired via the sep GitHub account.

4) Augment the tutorial to save each of the four figures to PNG files.

5) Get the f105w band image of the Hubble Ultra Deep Field, which is called

hlsp_hudf12_hst_wfc3ir_udfmain_f105w_v1.0_drz.fits

You can download it from https://archive.stsci.edu/pub/hlsp/hudf12/ (Links to an external site.).

6) Redo the tutorial steps in a second notebook, but on the UDF f105w image. How many sources do you find? Histogram their fluxes.

7) What are the mean, median, and standard deviation of the distribution of fluxes. What is the largest outlier in the distribution, where is it on the image, and how many standard deviations is it away from the mean? 

8) Download the f125w and f160w images of the HUDF at the same website, and make a 3-color false image of the UDF using RGB -> f160w, f125w, f105w. Save the image as a PNG.