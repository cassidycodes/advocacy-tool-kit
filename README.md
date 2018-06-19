# Advocacy Tool Kit

https://cassidy.codes/advocacy-tool-kit/

## Development

All development work happens on the `development` branch. The `master` branch is used for GitHub pages and is a git submodule of this repository.

- [Install Hugo](https://gohugo.io/getting-started/installing/):

```
brew install hugo
```

- Clone the repository.

```
git clone --recurse-submodules git@github.com:cassidycodes/advocacy-tool-kit.git
cd advocacy-tool-kit
```

- run hugo

```
hugo server
```

- deploy changes to the master branch

```
./deploy.sh
```
