# Drupal with Docker Compose

This is an example docker-compose setup (for each of [Drupal 7](drupal7) and [Drupal 8](drupal8))
that you might find useful if you need to migrate an application on a production server to some kind of
development environment. In my case, I was working with a version 7.x
Drupal installation on a private production server, and needed to be
able to reproduce the installation on my local machine to work with it. I
am providing these examples here in the case that they might help someone in
a similar situation. I added a Drupal 8 example since I'm aware that Drupal 7 is
going out of style.

## Dependencies

For each example setup, you will need to have [Docker](https://docs.docker.com/install/) 
and [Docker Compose](https://docs.docker.com/compose/) installed to your machine.

## Examples

 - [drupal-7](drupal7) is an example Drupal 7 application
 - [drupal-8](drupal8) is an example Drupal 8 application
