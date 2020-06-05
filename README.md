# apm-repo
Activity Package Manager manifest repository contains all packages manifest


## Adding your package:

Manifests are divided into folders by countries. Each folder contains main manifest, which contains only references, and activities, engines, wagons manifests. You are free to edit corresponding manifest yaml file (or create new if it is missing). Every manigest contains array of packages and package is this structure:

- package: unique package id in format packagetype/country/package name
- description: text desciption
- resources: list of main resources which this package contains 
- authors: text with athor names
- version: version  of this package
- downloader: downloader
- installer: installer
- dependencies: list of package IDs on which is this package dependent



For editing I recommend vscode + [yaml extension](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml), which will automatically validate yaml structure against json schema.


