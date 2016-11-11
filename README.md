# revokku
A circle CI and Bash Integration to deploy branches/tags from github to rancher docker containers
<HR>

Were going to use tags.  If it's not tagged with anything, it's dev, check it, dont deploy. If it's tagged as staging, check it, deploy to staging, update staging image. If it's master, keep it like we have, but also update the master image.
