---
layout: default
---

# Themes
Most of the UI responds to theme changes by adjusting colors to be appropriately tinted with color variations. We use an 8-part tinting scale where we add percentages of white to the `base` and `highlight` color of each theme. For example `.base__color--75` has 25% white added to the `base` color value.

### Night (default theme)

{% include theme.html %}

### Earth

{% include theme.html theme="Earth" %}

### Forest

{% include theme.html theme="Forest" %}

### Lava

{% include theme.html theme="Lava" %}

### Sea

{% include theme.html theme="Sea" %}

### Secondary Colors
We also have a few standard colors we don't change in the app when a theme switches. They are predominantly used for notifications.

{% include theme-standard.html %}