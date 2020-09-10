# README

Following tutorial:

[Let's Build: Instagram (Test Driven with Ruby on Rails) - Part 1](https://www.devwalks.com/lets-build-instagram-test-driven-with-ruby-on-rails-part-1/)

Pseudo-code, Creation of a post:

- visit the root route
- click on a button to create a new post
- fill out the bits of the form that we need.
- click the submit button
- expect the page that we’re sent to to have specific text
- expect the page to contain our photo.

Running the test:

```rspec

rspec /spec/features/creating_new_posts_spec.rb

```

Create a controller:
bin/rails g controller posts

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
