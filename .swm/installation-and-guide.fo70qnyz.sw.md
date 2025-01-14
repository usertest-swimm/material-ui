---
id: fo70qnyz
title: Installation and Guide
file_version: 1.1.3
app_version: 1.12.1
---

Material UI is our favorite React UI library and to be honest there isn't even a second UI library for React that we can even recommend. It's extremely difficult to make a good UI library for a variety of reasons. It's not just the amount of work it takes to produce components that are usable and look nice, but these components need to be documented well, have working examples, and support the endless amount of edge cases like responsiveness, accessibility, translation, theming and so on.

The amount of work that's been put into Material UI makes it our default choice for professional projects. If you've ever tried to build your own UI library you know how tedious it is to get the style and functionality right. So by choosing Material UI, you're saving yourself a lot of time that you can spend on building features for your project or business.

Check out this video we made going through everything in this article (and more):

<br/>

[<--VIDEO-->](https://youtu.be/CrHQBzwus3s)

<br/>

### Intalling Material UI

As we're going to show today the documentation is second to none. On their homepage you can see the installation and usage. You only need this one package `@material-ui/core` which you can install via npm or yarn. You may as well add the `@material-ui/icons` package if you intend to use icons.

You are then going to want to add in the stylesheet for the Roboto font to your main index.html file. This is really it, you can view the official installation instructions [here](https://material-ui.com/getting-started/installation/).

```
$ npm install @material-ui/core @material-ui/icons

// Add in your index.html file
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" />
// You may also want to add the Material icons font as well
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons" />
```

## **Using Material UI - Rendering a Button**

Using the components is simple. Just import the component from the library and render it like any other React component.

```
import React from 'react';

import { Button } from '@material-ui/core';
function App() {
  return <Button color="primary">Hello World</Button>;
}
```

import { Button } from '@material-ui/core';

function App() {

return <Button color="primary">Hello World</Button>;

}

The nice thing about the components is that they all contain their own styles, so there isn't a global CSS file that you have to worry about. Shortly we'll discuss a theme which controls properties like spacing and the primary color palette.

<br/>

## **How to Use Material UI Documentation**

On the Material UI site, click the upper left menu and you'll see a sidebar. We'll first talk about the two sections: Components and Component API. The main difference between these 2 sections is that the Components section contains examples/demos and explanations for each component while the Component API contains a complete list of all props and CSS rules/classes for each component (and no examples). Each component appears in both sections, creating a nice separation between exploration and checking exact property names.

## **Material UI Component Examples**

The Components section is where you're going to spend most of your time when researching how to use Material UI. The most important part about each component is that there are usually working examples on the page that you can try out.

For each example, you can see the full source code simply by clicking on the code icon: `< >` for each example. What you normally see on each component is a snippet of how to use the component, but more than likely you're going to want to see how that component was being used, the CSS that was applied, and the full list of imports. So that's why you will always want to click "show the full source" icon. You can even click "Edit in CodeSandbox" to instantly see the example within a live environment.

Best of all, these examples actually work, so you can copy the full code into your project, and then import the example into your project with minimal effort. The examples are usually creative and incorporate multiple elements from Material UI.

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://swimm-web-app.web.app/repos/Z2l0aHViJTNBJTNBbWF0ZXJpYWwtdWklM0ElM0F1c2VydGVzdGluZy1zd2ltbQ==/docs/fo70qnyz).
