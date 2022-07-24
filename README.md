# Nomad

## Learnings from wetube

### Beginning of the project

#### package.json
package.json should be created first.
```bash
npm i express
```
Then dependencies will be added to the package.json file.
As long as you have the package.json file, even if you move to different terminal, you can install all the necessary dependencies with this file, which will install according to what is written in the file. You can just write:
```bash
npm i
```
Then, it will install all the dependencies.

#### babel
When installing babel, it is under devDependencies, not dependencies. These two dependencies both go under node_modules folder, but it just distinguishes which dependencies are mainly used by whome.

#### Nodemon

