# mini-ci
small command line based ci server

## Why mini-ci?

Meeps Lab is a server that I am running on my local network with the intention of better learning systems architecture. It is a beefy server (ex: 128 gb of RAM), but a fully-fledged ci server seemed overkill for my use case. I basically just need something to poll my git repos for changes on a set interval and then build out docker containers on the Meeps Lab server accordingly. I first set out to host an existing CI server locally on my server, but this proved to be a bit too much of a hassle.

This is where mini-ci was born. Mini CI is a small CLI based CI tool to automatically pull and run code changes from the projects in this Github Organization. At the moment it is just a simple bash script, but if it grows more complex I'll rewrite it as a command line utility in Python or JavaScript.

## Usage

coming soon!
