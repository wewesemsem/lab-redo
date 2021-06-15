# Redoing the Lab

clone the repo locally, and make sure it works

```
$ git clone https://github.com/lennox-davidlevy/lab-redo.git
$ cd lab-redo
$ npm i
$ npm start
$ npm test
```

delete .git folder, and reinitialize git

```
$ rm -rf .git
$ git init
```

add files back in to git and commit

```
$ git add .
$ git commit -m "first commit"
```

sign in to Openshift

```
$ icc cohort9-bc-east
$ oc console
```

get argoCD login using igc

```
$ igc credentials
```
