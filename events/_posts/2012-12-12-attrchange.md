---
title: attrchange
---
# attrchange #

## Purpose ##

`"attrchange"` is triggered by Popcorn when any attribute of a media element is changed using Popcorn - i.e. `popcornInstance.controls( false )` . `"attrchange"` is to be used with the `on` and `off` instance methods.

For example:
* `popcornInstance.on( "attrchange", callbackFunction );`
* `popcornInstance.off( "attrchange", callbackFunction );`

## Use Cases ##

Monitoring a media element for attribute changes and updating visual information on a webpage about the medias state. i.e: volume, muted, playbackRate

## Examples ##

[Live demo using attrchange](http://jsfiddle.net/popcornjs/sywpR/)

