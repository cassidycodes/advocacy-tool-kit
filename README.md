# Advocacy Tool Kit

## Development

All development work happens on the `development` branch. The `master` branch is used for GitHub pages and is a git submodule of this repository.


- Clone the repository and initialize the submodule.

```
git clone --recurse-submodules git@github.com:cassidycodes/advocacy-tool-kit.git
cd advocacy-tool-kit
git checkout development
git submodule init
git submodule update
```

- Install dependencies

```
npm install
bower install
```

- serve the web app in development mode

```
gulp serve
```

- build to the `dist` directory

```
gulp
```

- deploy changes to the master branch, which will be published as a github page

```
./deploy.sh
```
