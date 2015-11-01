# Setting up your local environment

This workshop requires you to bring your own laptop and have the following prerequisites installed:

### Hardware requirements

* Operating System: Mac OS X (10.8 or later), Windows 7 (SP1), Fedora (21 or later)
* Memory: At least 4 GB+, preferred 8 GB

### Software requirements

* Java JDK -- [download here](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* Web Browser (preferably Chrome or Firefox)
* Git client -- [download here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Apache Maven -- [download here](https://maven.apache.org/download.cgi)
* VirtualBox -- [download here](https://www.virtualbox.org/wiki/Download_Old_Builds_4_3)
* Vagrant -- [download here](http://www.vagrantup.com/downloads.html)

Github.com access

The slides will walk you through setting up Docker and Kubernetes, etc

[http://redhatworkshops.github.io/slides/docker/generated/intro.html](http://redhatworkshops.github.io/slides/docker/generated/intro.html)

[http://redhatworkshops.github.io/slides/docker/generated/day1.html](http://redhatworkshops.github.io/slides/docker/generated/day1.html)

[http://redhatworkshops.github.io/slides/docker/generated/day2.html](http://redhatworkshops.github.io/slides/docker/generated/day2.html)

[http://redhatworkshops.github.io/slides/docker/generated/day3.html](http://redhatworkshops.github.io/slides/docker/generated/day3.html)

See this blog [for more info on each of the days](http://blog.christianposta.com/kubernetes/3-day-docker-and-kubernetes-training/)

## Generate slides
The sources for the slides are written in asciidoc and are prepared and packaged with revealjs using a wonderful tool named  [hyla](https://github.com/cmoulliard/hyla). To generate the slides, [install hyla]() and then from the root of this directory (after cloning it), run this:

> hyla generate -c slideshow/conference-redhat.yaml


## Credits

Huge shout out to the work [Kelsey Hightower](https://github.com/kelseyhightower/) does in the kubernetes community, and providing his [intro to kubernetes](https://github.com/kelseyhightower/intro-to-kubernetes-workshop) workshop on github.com I've used some of the `inspector` app RC and service definitions to illustrate the respective concepts.

For my slides, I used a lot of the [kubernetes.io documentation]() and some inspiration from Googler [
Satnam Singh's presentation tiled "Cluster management with Kubernetes"](http://www.slideshare.net/SatnamSingh67/2015-0605-cluster-management-with-kubernetes) and blog post [http://blog.raintown.org/2014/11/logging-kubernetes-pods-using-fluentd.html](http://blog.raintown.org/2014/11/logging-kubernetes-pods-using-fluentd.html)
