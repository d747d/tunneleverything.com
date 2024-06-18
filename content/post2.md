+++
title = "Tunneling web traffic over SSH"
date = 2024-06-18

[taxonomies]
categories = ["tunneling", "ssh", "browser"]
+++

One of the first and most common times I need to tunnel traffic is for viewing a browser session from a remote ip address where I only have SSH access to the remote server. Luckily, most SSH clients have the capability to tunnel traffic via local and remote ports. I'll be utilizing OpenSSH for this post since I live in a world of Linux generally, though you can still do this on Windows with something like Putty or MobaXTerm.

The first thing you'll need is a way to proxy the browser traffic to a different local port. For this I use [FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) (since I am a Firefox user for now).

![FoxyProxy Configuration Screenshot](./content/images/foxyproxyconfiguration.png)


<script data-goatcounter="https://tunneleverything.goatcounter.com/count"
        async src="https://gc.zgo.at/count.js"></script>
