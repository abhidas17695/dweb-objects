# DwebObjects
Object library for dweb extension.  Builds on dweb-transports.

## Background
This library is part of a general project at the Internet Archive (archive.org) 
to support the decentralized web.  

## Changes from general objects library

* Added browserify as devDependency

## Installation and usage in the Browser

* Clone this repo. 
* To install dependencies `npm install`
* To build the bundled javascript file `nom run-script build`. The file dist/objects-bundle.js is the output.

##See related:

* [Archive.org](http://dweb.archive.org/details) bootstrap into the Archive's page
* [Examples](http://dweb.me/examples) examples



###Repos:
* *dweb-transports:* Common API to underlying transports (http, webtorrent, ipfs, yjs)
* *dweb-objects:* Object model for Dweb inc Lists, Authentication, Key/Value, Naming
* *dweb-serviceworker:* Run Transports in ServiceWorker (experimental)
* *dweb-archive:* Decentralized Archive webpage and bootstrapping 
* *dweb-transport:* Original Repo, still includes examples but being split into smaller repos
