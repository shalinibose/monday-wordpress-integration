
<div align="center">
  <br>
  <h1> Monday-Wordpress Integration 👨‍💻</h1>
</div>
<br>
[![Twimbit](https://img.shields.io/badge/Powered%20by%20%7C-Twimbit-ef6d6c)](https://twimbit.com/?)

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/twimbit/wordpress-monday) [![Project demo](https://img.shields.io/youtube/views/OlHK9WsZCOY?style=social)](https://www.youtube.com/watch?v=OlHK9WsZCOY) 

![Project demo](https://img.shields.io/badge/Inspiration-Monday%20and%20Wordpress%20integration-0074a2?style=for-the-badge&logo=)
<br>

In our startup, we were using WordPress as a content publishing platform. Working with a team of people we found monday.com could be a great tool to manage the publishing, collaborate, and keep everything on track. So, we set-up a Monday board with automation and workflow that was suited for us. Monday soon we realized there was a lot of back and forth between Monday and WordPress in which users had to manually update things.
We saw this as an opportunity and started integrating with Monday API V2. As we built it on top of WordPress, we realized that we can actually extract the core and make it an open service for anyone using WordPress. 


## Introduction
This integration lets users synchronize there WordPress site with Monday to create efficient workflows and automation. Monday users can synchronize posts, pages, users, comments, and taxonomies from WordPress to Monday and vice versa. This opens a new window of automation opportunity for publishers, content creators, or simply anyone using WordPress to create custom workflows and connect various other platforms without any additional plugin installation on WordPress.

## Table of Contents

- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Benefits](#benefits)
- [How it works?](#how-it-works)
  - [Getting Started](#getting-started)
  - [Steps for installation](#steps-for-installation)
- [Vulnerability disclosure](#vulnerability-disclosure)
- [Contributing](#contributing)
- [Core team](#core-team)




## Benefits

### Monday users would be able to do following Integrations -
1.  When a WordPress Post is created create a new item and sync future changes.
Additionally -
a. Assign user if exists.
b. Assign Tags and categories using tags fields.
c. Load Comments as updates to the posts.
d. Synchronize post status and Monday status
e. Add the preview post link.
2.  When a WordPress Page is created create a new item and sync future changes.

3. When a new Monday item is created, Create a Draft post in WordPress.

4. When an item status changes to something, change WordPress post status to something

5. When a new WordPress user is added, create a new item on Monday

6. When a new Comment is added create a new item.

>  ......  Many more integrations coming soon.


## How it works?
The integration uses Monday V2 API with Authorization, custom triggers and actions, and WordPress Rest API. Since WordPress users can have any site, so to have a standard backend app, we have created a middleware application between Monday and WordPress that runs all the transaction on Standard URL’s. Price yet to be decided.


## Getting Started

Users will also need to install an additional WordPress plugin on their WordPress website and enter asked details during integration.

Install the plugin

| Plugin | Download file |
| ------ | ------ |
| GitHub | [Plugin](https://github.com/twimbit/wordpress-monday) |

##### Steps for Installation

1. Download this **[.zip file](https://github.com/twimbit/wordpress-monday)** .
2. Login to your WordPress Dashboard.
3. In your WordPress Admin Menu, go to Plugins > Add New.
4. Click on Upload Plugin button found on top left corner of page.
5. Click on Browse (1), Select the .zip file of your plugin in your computer, and click Install Now (2) button.
6. At this point, the plugin is installed. You can click on Activate Plugin link to work with it.
Well done, you have managed to install and activate your WordPress plugin !


### Vulnerability disclosure 🧑🏼‍💻

Monday-wordpress integration is the open source project. We welcome security research on this [open source project](https://github.com/twimbit/wordpress-monday/issues) .

### Contributing
We encourage you to contribute to this project!! ❤️ 


### Core team

| GitHub Usernames                                             | Domain     |
| ------------------------------------------------------------ | ---------- |
| Aman Sharma [(@amanintech)](https://github.com/amanintech)   | Full Stack |
| Siddhant Kumar [(@siddhantdante)](https://github.com/siddhantdante) | Full Stack |
| Gaurav Kumar [(icon-gaurav)](https://github.com/icon-gaurav) | Full Stack |





[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://github.com/twimbit)

