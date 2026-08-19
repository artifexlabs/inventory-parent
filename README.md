# inventory-parent
Parent POM for inventory work

## Goals

The inventory application is a boutique project developed to handle the specific sort of personal inventory issues that I experience.  While it may be useful to other people, it was written specifically for me.  Any and all feedback will be considered, but only as it benefits the initial goal (i.e. my inventory management problem).

* Keep a list of working items
* Hold par values and rotation schedules
* Keep track of my (multiple) locations for items
* Make any item a container
* Store data in the cloud with a local (offline-capable) backup
* Have a simultaneously available mobile client that handles scanning and image management
* Allow metatagging
* Allow for software/virtual assets

## POM

The POM for these components is based on the [InfrastructureBuilder Parent](https://github.com/infrastructurebuilder/ibparent) and will likely be kept up to the latest version of that.  Specific overrides and requirements for the inventory application will be made in this project.

## Build

The CI and release builds for this application are kept in a private Kubernetes cluster.  They are published to Maven Central for consumption, but may not be suitable for general use.

## Release

This application is expected to have a regular (possibly fast) release cadence.  Updates may be at a rate that is difficult to process for other people, which is unfortunate.  

## Versioning

This project deals strictly in [Semantic Versions](https://semver.org).  Older major versions are extremely likely to go unsupported.

