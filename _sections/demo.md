---
# order specifies where the section will be positioned relative to the other sections
# a higher number will appear later
order: 5

# anchor determines whether the section will appear in the navbar
# to use it, provide a string uniquely identifying the section
# the anchor is omitted here - you'll see that this section won't show up in the navbar
# anchor: 

# markdown supported field for the section title.
title: >
 # **Demo**
---
Here are what the headings look like:
# h1 (\#)
## h2 (\#\#)
### h3 (\#\#\#)
#### h4 (\#\#\#\#)
##### h5 (\#\#\#\#\#)
###### h6 (\#\#\#\#\#\#)

<br />

Add-on "modifiers" included with the theme:

<br />

{% raw  %}\{: .accent-color  \}{% endraw  %}
{: .accent-color}

<br />

{% raw  %}\{: .secondary-font  \}{% endraw  %}
{: .secondary-font}

<br />

{% raw  %}\{: .jumbo-font  \}{% endraw  %}
{: .jumbo-font}

Append these [Kramdown ALDs](https://kramdown.gettalong.org/syntax.html#attribute-list-definitions) after the line you want to style to use them. You can also chain them, just like how the intro at the top of the page uses "jumbo-font" and "accent-color". Here's the same combination again:

{% raw  %}\{: .accent-color .jumbo-font \}{% endraw  %}
{: .accent-color .jumbo-font }

Lastly, there's also a light and dark theme that is selected based on the visitor's system preferences. You can also set the dark theme to `always` on or `never` on.