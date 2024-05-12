# builds
This repository is setup to build a particular commit of csprite without
having to host the code at GitHub, essentially to just use GitHub Actions.

GitHub Rest API is used to trigger a build when I push to remote and then
pass the commit details.

For more details, Have a look at [post-push.sh](https://codeberg.org/csprite/csprite/src/branch/master/tools/post-push.sh).
