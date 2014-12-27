BIMserver-Repository
====================

Public repository for BIMserver services, plugins, extended data schema's and more

With this repository, we hope to make it easier for people to discover and publicize certain BIMserver related artifacts.

# Services

Services are pieces of logic, usually triggered by changes on a BIMserver. Services can be advertised here. There is a little more documentation on Services [here](https://github.com/opensourceBIM/BIMserver/wiki/Writing-a-remote-service).

# Extended Data Schemas

An Extended Data Schema is not a lot more than a globally unique namespace. It should help to classify pieces of Extended Data stored on a BIMserver. An example of this is the [BCF](http://www.buildingsmart-tech.org/specifications/bcf-releases) schema. By storing the Extended Data with a link to the BCF Extended Data Schema, software will know how to interpret the data. You could compare this to file extensions.

We have chosen to store the Extended Data Schema's on every BIMserver as well. This way developers can use their own schema's for development and testing purposes. The idea is that a BIMserver administrator decides which Extended Data Schema's are available for the normal users of the BIMserver, in order to regulate the use of Extended Data. The main reason for this being that Extended Data is specifically NOT meant to be used for storing all sorts of unclassified/unstructured data.

# Plugin

To be implemented, but the idea is to make plugins available here as well.

# Model Checker

Model Checkers are special plugins that can validate a model. To be implemented as well

# How to get your services etc... listed

Send us a pull-request, or request access to the repository
