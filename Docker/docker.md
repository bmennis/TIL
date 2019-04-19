# Docker
* Despite the convenience of having dockerfiles in one repo, it appears any changes made to any dockerfile in that repo trigger the rebuild of all images which can greatly slow things.
* With this in mind, may be best to put each dockerfile in it's own directory and try to name such directories to be clear as to what is contained.
* May want to try to build new docker images on quay first due to speed of building images, to check for success. It successful push to dockerhub.
* can log in to different docker registries from command line using docker login <registry>. for ex. cavatica registry is docker login cavatica-images.sbgenomics.com.
  * cavatica registry requires auth token for password.
  
