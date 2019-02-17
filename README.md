Learn Rails
================

----- start here -----

Installed from https://github.com/RailsApps/learn-rails
  - options: Getting the Application / Generate

## Getting Started

`$ gem list`

### Configuration File

From Here: http://railsapps.github.io/rails-environment-variables.html

#### Option One: Set Unix Environment Variables

`echo $SHELL`
_/bin/bash_

For a bash shell, using the Gmail example, edit the **~/.bashrc** file and add:

`export SENDGRID_USERNAME="myname@gmail.com"`
`export SENDGRID_PASSWORD="password=)"`

`export DOMAIN_NAME="???"`
`export MAILCHIMP_API_KEY="???"`
`export MAILCHIMP_LIST_ID="???"`
`export OWNER_EMAIL="denis.neverov@gmail.com"`
`export SECRET_KEY_BASE="???"`

e.g. `gedit ~/.bashrc`


#### Setup MailChimp

..To get `MAILCHIMP_API_KEY` and `MAILCHIMP_LIST_ID`


## Test the App

http://localhost:3000/ -- it works

Subscribed as _devlanev@yandex.ru_

See at [MailChimp Lists](https://us20.admin.mailchimp.com/lists/members?id=10843#p:1-s:10-so:null).

So, __it works!__


What's next? -- ## Deploy to Heroku






----- cut here -----

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

This application was generated with the [rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) gem
provided by the [RailsApps Project](http://railsapps.github.io/).

Rails Composer is supported by developers who purchase our RailsApps tutorials.

Problems? Issues?
-----------

Need help? Ask on Stack Overflow with the tag 'railsapps.'

Your application contains diagnostics in the README file. Please provide a copy of the README file when reporting any issues.

If the application doesn't work as expected, please [report an issue](https://github.com/RailsApps/rails_apps_composer/issues)
and include the diagnostics.

Ruby on Rails
-------------

This application requires:

- Ruby 2.4.2
- Rails 5.2.2

Learn more about [Installing Rails](http://railsapps.github.io/installing-rails.html).

Getting Started
---------------

Documentation and Support
-------------------------

Issues
-------------

Similar Projects
----------------

Contributing
------------

Credits
-------

License
-------
