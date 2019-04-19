# Quay
* Log in to quay chop @ https://quay.research.chop.edu
* If linking repos on quay to github, unlike dockerhub, you must have separate git repos for the different dockerfiles. If you do not split the dockerfiles it appears to pull and build on the latest updated dockerfile? Not entirely sure how quay goes about this but it is for sure that it is confused/does not handle repos with multiple dockerfiles.
