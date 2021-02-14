---
title: HyperlinkLabel
---

# HyperlinkLabel

This control takes a text string (like a Label), but you can annotate that string with text in [square braces].
By doing this, the text in square braces is automatically rendered as a hyperlink.
You can then register a callback to be notified when a user clicks on the hyperlinks in the text (and then do the correct thing, based on the selected hyperlink). 

Essentially, the use case is when you have a "[block of text](http://www.github.com/controlsfx/controlsfx) in [which you](http://www.github.com/controlsfx/controlsfx/wiki) want to [embed hyperlinks]({{< javadocurl >}}/)" (kind of like what I just craftily did right there).
In this situation you are left to painfully merge together Label and Hyperlink nodes, and hope everything works out. To save you this hassle, take HyperlinkLabel for a spin!

Here’s a thrilling screenshot of the control in action:

![HyperlinkLabel](/images/features/hyperlinkLabel.png "HyperlinkLabel")