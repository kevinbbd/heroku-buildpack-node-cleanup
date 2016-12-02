# heroku-buildpack-node-cleanup

Deletes the client nodejs app folder to decrease slug size

## Usage

    $ heroku buildpacks:set https://github.com/kevinbbd/heroku-buildpack-node-cleanup.git

Or add it to the .buildpacks file:

    $ cat .buildpacks
    ...
    https://github.com/kevinbbd/heroku-buildpack-node-cleanup.git
