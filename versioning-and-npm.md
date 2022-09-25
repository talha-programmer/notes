### Semantic Versioning
Example: "Express" : "4.15.8" 

Three parts of the version: 

- 1st part indicates the Major version 
- 2nd part indicates the Minor version 
- 3rd part indicates the Patch version 


**"Express" : "^4.15.8"**: 
It indicates that you can upgrade the Minor and Patch version, but keep the Major version same 


**"Express" : "~4.15.8"**: 
It indicates that you can upgrade only the Patch version 


### NPM
By default when we hit ``npm install`` command, it install the dependencies by using package.json file. If we want to use the exact dependencies mentioned in package-lock.json file, we can do that by this command ``npm ci``
