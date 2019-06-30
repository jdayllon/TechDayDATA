# #TechDayDATA

This repository contains several resources related to my presentation in #TechDayDATA on @sandetel last 2019.06.27.

## Objetive

This presentation covers the creation of simple and quite powerful active listing from Twitter social network for public administrations, like [Junta de Andalucia](https://www.juntadeandalucia.es) . Of course you can use for any target, like your personal profile or some term (or terms).

In this presentation I had told thet API-fication is need to get fast results without invest many resources or getting risks in a project that you don't have enough experience or knowledge, then i use AWS Comprehend for NLP analysis, Google Vision to extract entities from images attached and Bot-o-Meter to detect posible bots. You can enable or disable this part of process, or use your own credentials to use it.

## Resources

* [Slides](https://1drv.ms/p/s!AvxyNKQfVUXThhtF1qNF0pVTAPLx)
* Docker compose YAML files for 3 diferent contexts:
  * ElasticSearch & Kibana
  * Nuclio ServerLess platform
  * Apache Nifi
* Serverless functions for Nuclio
* Apache Nifi templates

## Reqs

To run this example you need Docker and Docker-compose, and I recomend 8 Gb of available memory and 20Gb of disk space, of course disk space depends of:

* Docker images and containers on your computer / system
* Range of time running the example and terms or profiles used as input

##  Future

This is a PoC. I had been working in another personal project (avaible on my profile) called [Saundweiv](http://github.com/jdayllon/saundweiv) and will update with several things lernaned in this development, i.e.:

* Getting Twitter info from stream like nifi and refresh info (like favs and rt)
* Make "my" own data model to enable other social networks (i.e. facebook or instagram)
* Add a serverless platform to make transformations easily.
* Use Kubernetes or origin (Redhat equivalent)