# slide-up-screen-navigation
Shows how to create sliding content panels.

On the web presenting large chunks of information remains a challenge. If there is a structure / architecture to be found in that information, we can organize and present the information one chunk at the time.

Accessibility advantages: presenting websites in a way that is less cluttered will help people affected by issues such as dyslexia, in addition to increasing focus on the actual content.

### The HTML
There are two important html blocks:
- the navigation, which is put inside a html5 nav tag.
- the main content, which is put inside a html5 main tag.

Inside the navigation element a header and series of links provide the menu.

Inside the main element a series of article tags is used for the sliding panels.
Each of these panels has a header, an image and some text.

The most important part of the html are the IDs of the articles. These IDs can be looked at as old fashioned anchors.
The links point to those IDs to make one of them active, triggering the appropiate styling.

The HTML is commented to make identifying the elements more convenient.

### The CSS
We make sure the navigation is positioned at a fixed location and always visible. By adding a z-index of 9999 it will always be on top, no matter what accidental content gets in the way.

The articles (panels) start out invisble and become visible only when targeted by the nav links.

The CSS is heavily commented to explain the individual rules.

## [Take a look at the live working version of this demo](https://arteessentia.github.io/slide-up-screen-navigation/)
