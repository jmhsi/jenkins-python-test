# steps I took after forking to make this work:

Changed versions of numpy and scipy in requirements.txt that were failing the build environment stage.
Had to sudo apt install sloccount
Make sure that I had Cobertura plugin in Jenkins
Make sure to install cucumber plugins in Jenkins
In post-always cucumber it threw error with parallel testing, so commented that line

# jenkins python ci/cd

Test repository for Jenkins based CI/CD of python project.


# Quickstart


Include `Jenkinsfile` in your project and connect it to the running Jenkins server.

For more details refer to this blog post:

[Setting Jenkins CI for python application](https://mdyzma.github.io/2017/10/14/python-app-and-jenkins/)
