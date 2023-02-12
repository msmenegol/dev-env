# Templates for setting up dev environment

Use these templates to create a docker container for running a given project inside a controlled environment. 

To use this in a project, simply clone the repor and copy the template files to a `dev_env` folder inside your project. Then, modify the files where indicated, and further add things as you see fit. For example, you might want to add more packages as you need them. On a python project, you could do that by installing the packages inside the container, exporting a `requirements` file, and adding the installation of said file in the Dockerfile.
