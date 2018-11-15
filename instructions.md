---
layout: lesson
title: WordPress Instructional
---

# Upload your static html site to Wordpress and make it user friendly.

## Introduction

Wordpress is a tool that many of us will have to become more familiar with as we start designing for clients. Clients who are not familiar with code language need to be able to manage their website and make simple changes if they need to, and Wordpress does this for them.

As we learned in Web 2, we as designers can create a static site to be designed just how we want, make it into a custom Wordpress theme, and then continue to put our content into Wordpress and create loops to make our content appear how we want. Doing this a lot of times either means sacrificing parts of our design, or making it extremely difficult for "normal" people to manage their website through Wordpress after we're done. So what are some ways we can accomplish this?

## Creating a Wordpress theme

By first creating a static site through html and css we can get our site to look exactly the way we want it to, and begin to make that into our custom Wordpress theme. To remember how to do this, you can just create a very simple page with a header, body, footer, and a few styles and follow the instructions we used during Web 2: https://github.com/philschanely/vcd-3600-content/blob/master/wordpress-themes.md

## Making it user friendly

Once your site is in place, we can now do several things to help make it more user friendly. [This article](https://premium.wpmudev.org/blog/simplify-wordpress-backend/) shows several ways you can do this, but we'll highlight some of them below.

### Make the client an editor
One way to do this is instead of allowing your clients to be administrators to the site in Wordpress, you can make them editors. This will remove a lot of settings and tools for them so they can manage the site better and don't accidentally change something that should not be changed. One downside to this is depending on how extensive they want to be able to make edits, it may take away some of the things they want to be able to use.

### Disable theme and plugin editing
This is another way to simplify what the client sees. Just put this code in your wp-config.php file:

define( 'DISALLOW_FILE_EDIT', true );

Doing this removes file editing options in the plugins and appearance section. The client doesn't need to have access to these files, and this will help simplify things for them.

### Use plugins
There are a variety of plugins you can use that help simplify things. For example, there is a plugin you can put in place to simplify menus and submenus so the client does not have to see things you do not want them to.

## Additional Tips
[This](https://torquemag.io/2017/05/make-wordpress-safe-for-clients/) is another good article that gives tips on how to make the site more friendly for clients.

One thing they recommend is to install the plugin called "Stream". This can be helpful once you are finished with the site and leave it in the hands of your clients. If your client ever contacts you saying something went wrong with the site, this plugin makes it much easier to see what went wrong. It tracks exactly what a user clicked and when they did it. This will make it much easier for you to fix any problems they may have.

## Conclusion
Wordpress is a great tool to have to help clients manage their own sites once we're done with it. Wordpress can be difficult to make a site look just how we want knowing we'll have to hand it over to our clients. Knowing ways to simplify Wordpress and make it more user friendly for our clients is one way we can help our client's confusion, and our peace of mind as designers.
