# Borders

The Borders API is a simple (and still relatively exploratory) API that allows you to easily wrap panes or nodes with a border, similar to the Swing BorderFactory API.
Here’s a some code, and then a screenshot of what that code results in:

``` java
Node wrappedButton = Borders.wrap(button)
.lineBorder().color(Color.RED).build()
.lineBorder().color(Color.GREEN).build()
.build();
```

![A single button with two borders](/images/features/borders-twoLines.png "A single button with two borders")
