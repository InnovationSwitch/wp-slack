<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# Slack

Send notifications to Slack channels when certain events in WordPress occur.

**Contributors:** [akeda](http://profiles.wordpress.org/akeda)  
**Tags:** [slack](http://wordpress.org/plugins/tags/slack), [api](http://wordpress.org/plugins/tags/api), [chat](http://wordpress.org/plugins/tags/chat), [notification](http://wordpress.org/plugins/tags/notification)  
**Requires at least:** 3.6  
**Tested up to:** 3.8.1  
**Stable tag:** trunk (master)  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  
**Donate link:** http://goo.gl/DELyuR  

## Description ##

This plugin allows you to send notifications to Slack channels when certain events in WordPress occur.

[![Play video on YouTube](http://i1.ytimg.com/vi/wPFT22cWxRQ/hqdefault.jpg)](http://www.youtube.com/watch?v=wPFT22cWxRQ)

By default, there are two events that can be sent to Slack:

1. When a post is published
1. When there's a new comment

It's possible to add more events using `slack_get_events` filter. For more information check [the doc](http://gedex.web.id/wp-slack/).

The new event will be shown on integration setting and if enabled anytime a user is logged in you'll get the notification in Slack.

**Development of this plugin is done on [GitHub](https://github.com/gedex/wp-slack). Pull requests are always welcome**.

## Installation ##

1. Upload **Slack** plugin to your blog's `wp-content/plugins/` directory and activate.
1. Add new **Incoming WebHooks** service in your Slack, the URL is `https://<SUBDOMAIN>.com/services/new/incoming-webhook` (replace `<SUBDOMAIN>` with your Slack's subdomain). Once created, note the URL of the service (you'll set it into integration entry in your WordPress).
1. Go to **Slack** menu in your WordPress to add the integration (make sure you're logged in as an Adminstrator).

## Screenshots ##

### Integrations list. Yes, you can add more than one integration.

![Integrations list. Yes, you can add more than one integration.](assets/screenshot-1.png)

### Edit integration screen.

![Edit integration screen.](assets/screenshot-2.png)

### Your channel get notified when some events occur.

![Your channel get notified when some events occur.](assets/screenshot-3.png)

## Changelog ##

### 0.1.0 ###
Initial release


