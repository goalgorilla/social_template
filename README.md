This is a composer based installer for the [Open Social distribution](https://www.drupal.org/project/social).

# Prerequisites

1. [Composer](https://getcomposer.org/download/)

It's just composer, isn't it awesome? :)

## Installation of Open Social

```
composer create-project goalgorilla/social_template:dev-master DIRECTORY --no-interaction
```

Composer will create a new directory called DIRECTORY.
The installed folders will contain all Drupal related files in the `html`
directory and any third-party dependencies in the composer `vendor` directory.
Drupal core will be installed to `html/core`. Inside you will find the
html directory with the entire code base of the [Open Social distribution](https://www.drupal.org/project/social).
Install your Open Social site like any other Drupal website using the `install.php` script or `drush`.

## Learn more about Composer for Drupal

Checkout this [presentation](https://docs.google.com/presentation/d/1gxcxT6o47xVrfsZ7ZSQKjBRT-gfE54A1Z9kjvvGHwCo/edit#slide=id.p) from @ModsUnraveled.

## Issues

### Install issues for Open Social
[documentation](https://www.drupal.org/docs/8/distributions/open-social/installing-and-updating)

### Installing outside of HTML folder
[See this issue for more information](https://www.drupal.org/project/social/issues/2792543#comment-11591981)

### Open Social issues & Support
For any issues with the platform we kindly ask you to use the [drupal.org](https://www.drupal.org/project/issues/social) issue queue.
This way we can centralise all the information and make the feedback available 
for other users for documentation purposes. Next to giving people the credit they deserve.

### **Slack**
If you have a quick question, we are also available on Slack. Visit https://www.drupal.org/slack to see how you can join Drupal Slack. After that you can find us in the #opensocial channel. We try to keep an eye on this channel but it may take a bit of time to get to you. For bug reports or longer questions, please use the Issue queue on Drupal.org so others can find the answers too.
