# dashing-server-monitor
A simple server monitor for the Dashing dashboard.

(Originally located at https://gist.github.com/willjohnson/6313986 but moved to a repo to better track changes)

Description
===========

A [Dashing](https://github.com/Shopify/dashing) widget that checks whether a server is responding to either an http or ping request. It displays either a check or alert depending on the response.

![](http://i.imgur.com/chZNAbx.png)

Usage
=====

1. Add the widget HTML to your dashboard

```html 

    <li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
      <div data-id="server_status" data-view="ServerStatus" data-title="Server Status"></div>
    </li>
```
    
2. Create a directory titled "server_status" under your widgets directory and move server_status.coffee, server_status.html, and server_status.scss into that directory.

3. Modify the servers array of the server_status.rb file.

4. Move server_status.rb into your jobs folder.
