## New Lando Drupal Setup

* Make new directory and cd into it
* `lando init` 
* Use drupal 8 receipe
* Use `web` for webroot
* Name it
* `lando composer create-project drupal-composer/drupal-project --stability dev --no-interaction temp`
* `mv temp/* .`
* `mv temp/.* .`
* `rm -rf temp`