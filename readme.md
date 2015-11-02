# Development environment for the twbs-blade package
Basically a standard [Laravel](http://laravel.com/docs) installation that requires
[fewagency/twbs-blade](https://github.com/fewagency/twbs-blade).

## Development installation
1. Clone the git-repository into a directory of your choice - preferable in your [Homestead virtual machine](http://laravel.com/docs/homestead).
2. In the project directory, run `composer create-project` to create a default `.env` file.
3. Edit your `.env` file to configure your development environment to your liking
4. Set up the site to be served by a webserver - preferable in your [Homestead.yaml file](http://laravel.com/docs/5.1/homestead#configuring-homestead).
5. Install the repo version in the project directory `composer install fewagency/twbs-blade --prefer-source`

[Configure PhpStorm](https://github.com/fewagency/best-practices/blob/master/Configure%20PhpStorm%20for%20Laravel%20project.md) if relevant.