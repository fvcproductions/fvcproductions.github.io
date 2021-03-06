---
title: PWA Roadshow
date: 2017-10-22
description: The Progressive Web App Roadshow is a series of events that explains the what, why and how of PWAs and allows participants to work through some code labs that provides hands-on experience.
image: https://gdg-korea-webtech.firebaseapp.com/pwa-roadshow17/roadshow.jpg
categories:
  - conference
  - program
---

## Name

[Progressive Web App Roadshow San Francisco 2017](https://events.withgoogle.com/progressive-web-app-roadshow-san-francisco-2017/)

## Location

Google Launchpad Space - 301 Howard Street San Francisco, CA - 4th Floor

## Date

Sunday, October 22nd - 9:00 AM to 5:00 PM

## Role

_Participant_ - I participated this event as part of the [Chrome Dev Summit](https://developer.chrome.com/devsummit/). Registration was super limited so I'm glad I was able to attend.

## About

The **Progressive Web App Roadshow** is a series of events that explains the what, why and how of PWAs and allows participants to work through some code labs that provides hands-on experience.

> What are PWAs?

Progressive Web Apps are experiences that combine the best of the web and the best of apps. They load quickly, even on flaky networks, can re-engage with users by sending web push notifications, have an icon on the home screen and load as top-level, full screen experiences.

### Topics Covered

#### Overview

* [PWAs](https://developers.google.com/web/progressive-web-apps)
  * [Twitter Lite](https://mobile.twitter.com/home)
  * [Lancome](https://lancome.com)
  * [Lyft](https://ride.lyft.com)
* [Google's Udacity Courses](https://www.udacity.com/google)

#### Integration

* [High Conversion Web Forms](https://developers.google.com/web/fundamentals/design-and-ux/input/forms/#recommended_input_name_and_autocomplete_attribute_values)
* [Payment Request API](https://developers.google.com/web/fundamentals/payments/)

#### Reliability

* [Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers/)
* [Lie-fi](https://www.urbandictionary.com/define.php?term=lie-fi)
* [Workbox](https://workboxjs.org/)

#### Engaging

* [Web Push Notifications Library](https://github.com/web-push-libs/web-push)
* Web Push Notifications
  * Carnival
* Good Notifications
  * Timely
    * Matters right now
  * Relevant
    * User cares about it
  * Precise
    * Exact details
* How Push Works
  * Client Side
    * Get permissions to send notifications
    * Subscribe & get `PushSubscription`
    * Send `PushSubscription` to server
  * Server Side
    * Create message on server
    * Use Web Push Protocol to send
      * All browsers use `Web Push API`
    * Push Service delivers message
    * Message arrives on device
    * Browser wakes up service worker
    * Handle `push` event and shows notification
  * Application security keys
    * public
      * used for subscription
    * private
      * used to send messages
  * Subscribing and unsubscribing
    * Is web push supported?
    * Check subscription status
    * Subscribe to user
      * `userVisibleOnly`
    * Promoting and permission
      * First ask, then prompt
      * Weather.com
        * gives options

#### Security

* `HTTPS`
  * identity
  * confidentiality
  * integrity
* Man in the middle attacks
* First get `HTTPS` then extend to `HTTP/2`
* Certificate
  * [Let's Encrypt](https://letsencrypt.org/)
* Referrer Policy

### Lighthouse

* Available in Chrome DevTools & as a command line tool.
* Aim for 90 and above on all metrics
  * PWA
  * Performance
  * Accessibility
  * Best Practices

### Codelabs

* [Your First Progressive Web App](https://goo.gl/ubLX3o)
* [Debugging Service Workers](https://goo.gl/QY5FFL)
* [Adding Push Notifications](https://goo.gl/Mt2n5k)
* [Frictionless Payments with the Payment Request API](https://goo.gl/SV4tgJ)

### Photos

> And I'm pumped!

![The Bar](https://i.imgur.com/VMhsM6T.jpg)

> Where I was sitting

![Where I was sitting](https://i.imgur.com/tmjYbEF.jpg)
