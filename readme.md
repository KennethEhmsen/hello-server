# Hello Server by Liquid Web
Contributors: Liquid Web, liquidwebdan, liquidweb
Tags: server info, hostname, cluster, clustering, multi-node, webnodes, web-nodes, multi-server
Requires at least: 3.0
Tested up to: 4.8.0
Stable tag: 1.2.1
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This is a simple plugin that tells you what server your WordPress is running on. It's super useful for when you run WordPress in a clustered, or mulit-server, environment.

## Description

Do you run your WordPress in a Cluster based setup?  
Ever need to know what server your request came from?  
Don't want to have to dig into server access logs to do it?  

Look no further, this is just the plugin you're looking for.

Hello Server adds a menu-node to the Admin Toolbar that tells you what server your request was sent from! In the new Hello Server menu you'll find the current servers hostname and IP!

## Screenshots

1. Basic WordPress toolbar with Hello Server menu
2. Hello Server menu expanded showing server details
3. 'Close up' of just the Hello Server menu

## Frequently Asked Questions

1. So what's this do then?

    Basically this plugin will tell you the servers hostname that your WordPress is executing on. This means if you're in a shared environment it will report the shared servers hostname. If you're in a clustered environment then it will report the hostname that handled the request.

2. Is this only useful for Clustered setups?

    No, but they benefit the most from it.

    It saves users the time and effort it takes to SSH into servers and tail log files. This plugin could also be useful for WordPress users hosted via a Platform as a Service (PaaS).

## Installation

Automated Install:

*   Go to plugins page in WordPress admin
*   Search for 'Hello Server'
*   Click 'Add to WordPress'
*   Activate plugin

Manual Install:

*   Download zip to WordPress plugins folder.
*   Extract zip contents
*   Activate plugin

## Changelog

### 1.2.1

*   Improve transient implementation to prevent showing inaccurate information.

### 1.2.0

*   Use transient to make things a little snappier.

### 1.1.0 & 1.1.1

*   Add support for l10n and i18n.
*   Add multiple language translations.

### 1.0.3

*   Fix docs

### 1.0.0 & 1.0.1

*   Clean up all the things.
*   Improve docs.
*   Clean up all the things.
*   First public releases.

### 1.0a

*   Initial version & POC