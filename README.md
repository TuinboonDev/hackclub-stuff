# Cloaked (reverse proxy)

<img widht="640" height="360" src="http://git.thijmens.nl/Tuinboon/reverse-proxy/raw/branch/main/banner.png">

A reverse proxy written in Rust using no particular HTTP library.

# How to use

You can `git clone http://git.thijmens.nl/TuinboonDev/reverse-proxy.git` the repo and run `cargo run` to get started.<br>
A demo of this is running, <a href="#">right here right now</a>.<br>
When you encounter any issues please dm me on discord (tuinboon) or submit a PR? :)<br>

For an example config file check <a href="http://git.thijmens.nl/TuinboonDev/reverse-proxy/src/branch/main/config.json">here</a> or checkout the other branches for the <a href="http://git.thijmens.nl/TuinboonDev/reverse-proxy/src/branch/html_lib">HTML_LIB</a> and <a href="http://demo.thijmens.nl/">a custom site using it</a> 

# What?
A reverse proxy written in Rust using no particular HTTP library.<br>
The proxy can either proxy or host websites, hosted websites make use of a custom library.<br>
It uses libloading to load all websites and enable hot reloading.<br>

# Why?
I don't exactly remember but I think I started this project because I just kept spinning up cloudflare tunnels.<br>
Since I always want to have done/ do things myself (the reason im not using a HTTP library) I wanted to control my own hosting.<br>
Instead of opening countless ports on my server I decided to write a reverse proxy.<br>

