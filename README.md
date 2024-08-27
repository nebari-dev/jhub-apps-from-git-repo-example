# JHub Apps application from Git repository

[![Test](https://github.com/nebari-dev/jhub-apps-from-git-repo-example/actions/workflows/test.yml/badge.svg)](https://github.com/nebari-dev/jhub-apps-from-git-repo-example/actions/workflows/test.yml)

An example of creating jhub-apps from a git repository using [conda-project](https://conda-incubator.github.io/conda-project/).

## Installation

```bash
# add --force for installing with updated dependencies
conda project install
```

## Running the project

```bash
conda project run
```

Now got to http://127.0.0.1:5000 to see the panel app in action.


## Configuration file (`.conda-project.yml`)

The configuration file for deploying the app on jhub-apps is defined via conda-project's yaml spec.
The documentation for the same can be seen here: https://conda-incubator.github.io/conda-project/user_guide.html#the-conda-project-yml-file

The sample configuration file in this repository (`conda-project.yml`) can be used to deploy panel app
on jhub-apps. The configuration file can be updated along with other assets like the file in the `filepath`
variable to deploy app for any framework [supported by jhub-apps](https://jhub-apps.nebari.dev/docs/category/create-apps) for that matter.
