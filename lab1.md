
# Goals for the lab

- [ ] Login to subliminal, set up COMPBIO area.
- [ ] Use R from the command line, Rstudio.
- [ ] Start working through DMB handout.

# Set up subliminal

```sh
ssh -Y sje30@subliminal.maths.cam.ac.uk # change to your CRSID
```

(-Y means that you need

**One time only** you will need to run the following program to configure
your logins:

```sh
/alt/applic/user-maint/sje30/COMPBIO/compbio_runmeonce.sh
```

Hint: hit TAB to complete filenames.

Logout and then log back in to subliminal and try to run julia to
check that you have everything setup:

```sh
julia-0.4.0-rc4
```

Control-d to exit.

Check which machine you are on by running `uname -a`

## Check you can run R

```sh
    R
    4*2
    require(limma)
```


Control-D to exit.

## Check you can run Rstudio

    rstudio



# Start the Dynamic Models in Biology

Go through as far as you can, and at least until the end of section 10.



