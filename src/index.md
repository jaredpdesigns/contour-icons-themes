---
layout: default
---

# Default

The default set of icons is what we use the most often in our interface.

{% include icons.html category="default-" %}

# Placemarkers

Placemarkers are used predominantly in the ‘Draw & Annotate’ panel when users select to place a marker. 

{% include icons.html category="marker-" %}

# Multi-Tonal

Multi-tonal icons are used a bit more sparingly in the interface but serve an important role. Unlike the other icons, each SVG is composed of two paths, one for the top and one for the background of the icon. The background path has an opacity of 25% and can be easily overridden with CSS by declaring `.svg-class .icon__bg { opacity: 1; }`.

{% include icons.html category="multi-" %}