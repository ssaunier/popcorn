Popcorn
=======

Getting Started
---------------

This repository comes equipped with a self-setup script:

    % ./bin/setup

After setting up, you can run the application using [foreman]:

    % foreman start

[foreman]: http://ddollar.github.io/foreman/

Guidelines
----------

Use the following guides for getting things done, programming well, and
programming in style.

* [Protocol](http://github.com/thoughtbot/guides/blob/master/protocol)
* [Best Practices](http://github.com/thoughtbot/guides/blob/master/best-practices)
* [Style](http://github.com/thoughtbot/guides/blob/master/style)


TODO
====

- Scaffold movie model
  - title
  - director
  - country
  - picture_url
- User model + Devise
- Fetch new movies from External source
- User has many MoviesToWatch (model)
  - watched (boolean)
  - list_name (string)  to_watch, meh, nope
- Incoming Page - next movie to show
- Incoming Page action buttons
- To Watch and Meh Page
- Mark a movie as watched
- Keyboard Shortcuts Watch / Meh / No