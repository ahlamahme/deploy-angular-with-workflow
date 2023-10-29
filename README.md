# AngularDeploy2

In this project I use github Actions to build and deploy angular small project.

## workflow

The workflow contain two jobs and deploy:


## In build job 
I install dependences like Nodejs and angular cli and run ng build command 
build job has to be on main branch

## In deploy job

I checkout to the gh-pages branch becouse the built source code on it.
I change the base herf to mach the deploy URL using bash (sed)


