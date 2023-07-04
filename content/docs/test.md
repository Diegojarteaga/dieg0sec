---
title: "Test"
date: 2023-07-04T13:36:35-05:00
draft: false
---
## Installing Hugo and creating our site
First things first we need to install Hugo by referencing Hugo's documentation [Here](https://gohugo.io/installation/). 

I'm on Linux using Debian so I'll run the following command:
```
sudo apt install hugo
```

Once Hugo is installed we'll run the following command to generate our new site:
```
hugo new site dieg0sec -f yml
```
We are passing in the optional "-f yml" to change the configuration file to a yml instead of the default toml.

Navigate to the site directory we just created and lets create a test page.
```
hugo new docs/test.md
```

