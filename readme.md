# Development environment for the twbs-blade package
Basically a standard [Laravel](http://laravel.com/docs) installation that requires
[fewagency/twbs-blade](https://github.com/bjuppa/twbs-blade).

## Development installation
1. Clone the git-repository into a directory of your choice - preferable in your [Homestead virtual machine](http://laravel.com/docs/homestead).
2. In the project directory, run `composer create-project` to install dependencies and create a default `.env` file.
3. Edit your `.env` file to configure your development environment to your liking
4. Set up the site to be served by a webserver - preferable in your [Homestead.yaml file](http://laravel.com/docs/5.1/homestead#configuring-homestead).

### Set up git repo for twbs-blade
Install the repo version in the project directory (you may need to delete the directory `vendor/fewagency/twbs-blade` first)
> composer update fewagency/twbs-blade --prefer-source

Go into the package directory
> cd vendor/fewagency/twbs-blade

Make the current branch of the twbs-blade package push to a remote where you have permissions (modify this command as needed)
> git branch -u origin/fluent-html
