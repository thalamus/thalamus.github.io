---
layout: post
title: "Code, blockquotes and a new font"
date: 2019-08-28 11:55
---
This post is more to mess about testing the capabilities of jekyll than anything useful.
I've also updated the site font to the excellent [Overpass font](http://overpassfont.org/), and am using both the Sans Serif and Monospaced variants.

The below is just some stuff for the hell of it.


-Will


> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

```bash
#!/bin/bash

###### CONFIG
ACCEPTED_HOSTS="/root/.hag_accepted.conf"
BE_VERBOSE=false

if [ "$UID" -ne 0 ]
then
 echo "Superuser rights required"
 exit 2
fi

genApacheConf(){
 echo -e "# Host ${HOME_DIR}$1/$2 :"
}

echo '"quoted"' | tr -d \" > text.txt
```