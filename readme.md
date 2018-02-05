# Choosing a React Component Library

There are many React component libraries that have already been developed, are actively maintained, and are ready to use on your project. Using an existing component library will help keep your code readable and maintainable, speed-up your development and help you ship your product faster. This talk will guide you through some of the available options and help you choose a library that best fits your project!

Component libraries allow you to speed up UI development.
They often enforce development approaches and best practices.
They minimize decision fatigue.
They allow you to ship an MVP / product faster.
They help keep your code readable and maintainable.

Choosing a library will depend on what you need.
There are a shitton of options out there.

Matthew Holman is an entrepreneur, React enthusiast and frontend developer for Cylance. He has been developing with React since 2016 and has made several open source React contributions. He focuses his day to day work within the React ecosystem and has built an impressive collection of unfinished side projects. In his spare time, Matthew likes to annoy with his wife and children, drink craft beer and code -- sometimes in unison!

---

# Material Design

Google’s UI development paradigm builds on years of research and is familiar to millions of users. It is wildly popular and there are many component libraries based on the [Material Design Guidelines](https://material.io/guidelines/#).

## [Material-UI](http://www.material-ui.com/)
Material-UI is a set of React components that implement Google's Material Design specification. Material-UI components work in isolation. They are self-supporting, they will inject, and only inject, the styles they need to display. They don't rely on any global styles like normalize.css, although Material-UI does provide an optional Reboot component.

* Current version: 0.20.0
* Contributors: 636
* GitHub Stars: 32,572
* Open bugs / issues: 12/138
* Maintainers: Olivier Tassinari & Community
* License:


## [React-Toolbox](http://react-toolbox.io/)
Just like Material UI, React-Toolbox favors Google’s Material Design. It is a collection of UI components based on CSS modules with locally-scoped class names. Still, there’s support for customization and theming with react-css-themr being the recommended tool for both the current and the future version.

* Current version: 2.0.0-beta.12
* Contributors: 218
* GitHub Stars: 7,568
* Open bugs / issues: 12/199
* Maintainers: Javi Velasco | Javi Jiménez | Community
* License: MIT

## [React MD](https://react-md.mlaursen.com/)

* Current version: 1.2.11
* Contributors: 41
* GitHub Stars: 1,566
* Open bugs / issues: 47 / 122
* Maintainers: Mikkel Laursen | Community
* License: MIT

## [React-materialize](https://react-materialize.github.io/)

* Current version: 1.1.2
* Contributors: 43
* GitHub Stars: 768
* Open bugs / issues: 2 / 47
* Maintainers: Community
* License: MIT

## [React Material Components Web](https://jamesmfriedman.github.io/rmwc/)

* Current version: 1.1.1
* Contributors: 9
* GitHub Stars: 290
* Open bugs / issues: 1 / 12
* Maintainers: James Friedman
* License: MIT

---

# Bootstrap
Bootstrap is a popular free and open-source front-end web framework. There are several component libraries that have been built around the bootstrap framework.

## [React-Bootstrap](https://react-bootstrap.github.io/)
React-Bootstrap was pioneered by Matthew Honnibal, Stephen J. Collings, and Pieter Vanderwerff. The project is in active development, but still on a roadmap for a 1.0.0 release. It currently offers an implementation of Bootstrap 3 styling encapsulated into React components. It allows you to create and modify such components using JS objects or JSX without having to worry about potential abstraction issues.

* Current version: 0.32.1
* Contributors: 198
* GitHub Stars: 12,110
* Open bugs / issues: 4 / 43
* Maintainers: Matthew Honnibal, Stephen J. Collings, and Pieter Vanderwerff | Community
* License: MIT

## [Reactstrap](http://reactstrap.github.io/)
Reactstrap is an easy to implement component library that already utilizes many of the Bootstrap 4 components.

* Current version: 4.8.0
* Contributors: 79
* GitHub Stars: 3,436
* Open bugs / issues: 5 / 70
* Maintainers: Eddie Hernandez, Evan Sharp & Community
* License: MIT

---

## [Ant Design](https://ant.design/)
Ant Design is way more that just a React library or framework. It’s a massive ecosystem with a proprietary style guide, custom Webpack-based build tool and custom CLI applications. The project is really well-polished, with giants like Alibaba and Baidu using it. There are more than 50 React components within the library at this time!

* Current version: 3.1.6
* Contributors: 426
* GitHub Stars: 23,571
* Open bugs / issues: 20 / 174
* Maintainers: Ant Financial
* License: MIT

## [Semantic UI React](https://react.semantic-ui.com/introduction)
This library promises a clean React-friendly implementation of Semantic UI with its minimalist out-of-the-box styling. The original vision behind Semantic UI comes down to the use of standard React components that developers can modify and expand.

* Current version: 0.77.2
* Contributors: 163
* GitHub Stars: 5,719
* Open bugs / issues: 19 / 76
* Maintainers: Semantic Organization
* License: MIT

## [Blueprint](http://blueprintjs.com/)
Blueprint is a component library with a primary focus on building data-heavy interfaces for desktop screens. Being essentially desktop-first, it doesn’t offer much in the way of mobile UIs, which is an important thing to consider.

* Current version: 1.35.2
* Contributors: 82
* GitHub Stars: 8,189
* Open bugs / issues: 73 / 302
* Maintainers: Palantir
* License: Apache 2.0

## [Fabric](https://developer.microsoft.com/en-us/fabric#/components)
The official React components library from Microsoft, Fabric brings the aesthetic of MS Office to third-party web apps. Much like Material Design, Fabric is a complete design language rather than a collection of “starter-pack” styles that you will heavily modify.

One tricky thing with the library is the licensing of the fonts and brand icons. While the library itself is MIT-licensed, the fonts and brand icons from MSFT aren’t. This means they might be out of reach if you’re working on an independent project, which seems like a downer.

* Current version: 5.44.0
* Contributors: 209
* GitHub Stars: 2,208
* Open bugs / issues: 111 / 401
* Maintainers: Microsoft
* License: Partial MIT

## [Grommet](http://grommet.io/)
Grommet makes a great first impression thanks to its neat documentation, style guide, and its huge number of available UI components. Furthermore, it offers a solid enterprise-grade solution complete with a full-fledged design language.

Being a project of Hewlett Packard, Grommet reflects the company’s vision of UX best practices, which might feel a little too specific. In fact, developers claim the framework’s component structuring is somewhat restrictive, with certain components only accepting certain children, nested in a certain way.

* Current version: 1.10.0
* Contributors: 98
* GitHub Stars: 2,851
* Open bugs / issues: ? / 95
* Maintainers: Hewlett Packard
* License: Apache 2.0

## [Rebass](http://jxnblk.com/rebass/)
Rebass uses styled components and enables developers to implement architecture patterns based on the separation of concerns between presentational and container components. This approach leaves you writing container components to handle application logic and higher-level architecture, but it also allows for greater flexibility. Rebass appears to be in a state of inactivity for the last 6 months.

* Current version: 1.0.4
* Contributors: 26
* GitHub Stars: 3,386
* Open bugs / issues: ? / 43
* Maintainers: Brent Jackson
* License: MIT

## [React Desktop](http://reactdesktop.js.org/)
React Desktop is different from other libraries on this list because it’s essentially a small collection of Windows and macOS UI elements.

Specifically, we’re talking about 19 macOS and 12 windows components mimicking native UI elements of the two operational systems.

* Current version: 0.3.3
* Contributors: 14
* GitHub Stars: 7,053
* Open bugs / issues: 7 / 24
* Maintainers: Gabriel Bull
* License: MIT

## [Pivitol-ui-react](https://styleguide.pivotal.io/)

* Current version: 13.0.1
* Contributors: 64
* GitHub Stars: 524
* Open bugs / issues: ? / 6
* Maintainers: Pivotal Software Inc
* License: MIT

## [Belle](http://nikgraf.github.io/belle/)

* Current version: 3.0.2
* Contributors: 19
* GitHub Stars: 2,106
* Open bugs / issues: 4 / 46
* Maintainers: Nik Graf
* License: MIT

## Onsen UI
Mobile app development framework and SDK using HTML5 and JavaScript. Create beautiful and performant cross-platform mobile apps. Based on Web Components, and provides bindings for Angular 1, 2, React and Vue.js. Great docs!

* Current version: 2.9.1
* Contributors: 86
* GitHub Stars: 5,953
* Open bugs / issues: 7 / 47
* Maintainers: Monaca & Onsen UI team
* License: Apache 2.0

## [Elemental UI](https://github.com/elementalui/elemental)

* Current version: 0.61
* Contributors: 29
* GitHub Stars: 3,938
* Open bugs / issues: 1 / 37
* Maintainers: Thinkmill
* License: MIT

## [React-foundation](https://react.foundation/)

* Current version: 0.9.2
* Contributors: 6
* GitHub Stars: 382
* Open bugs / issues: 1 / 10
* Maintainers: Digia
* License: MIT


## [admin-on-rest](https://marmelab.com/admin-on-rest/)
A frontend Framework for building admin applications running in the browser on top of REST services, using ES6, React and Material Design.

* Current version: 1.3.4
* Contributors: 115
* GitHub Stars: 3,508
* Open bugs / issues: 8 / 51
* Maintainers: Marmelab
* License: MIT

## [React Virtualized](http://www.reactvirtualized.com/)
React components for efficiently rendering large lists and tabular data

* Current version: 9.18.0
* Contributors: 139
* GitHub Stars: 8,726
* Open bugs / issues:
* Maintainers:
* License: MIT

## [SearchKit](http://docs.searchkit.co/stable/index.html)
SearchKit is a suite of UI components built in react. The aim is rapidly create beautiful search applications using declarative components, and without being an ElasticSearch expert.

GitHub Stars: 3,207

## [Mulesoft](http://ux.mulesoft.com/#/)
GiHub Stars: 552

## [PrimeReact](https://primefaces.org/primereact/)

GitHub stars: 274

## [Design System React](https://react.lightningdesignsystem.com/)

GitHub stars: 86

## [Khan Academy](https://khan.github.io/react-components/)
GitHub stars: 934


## Resources

* [Devarchy](https://devarchy.com/react/topic/ui-framework)
* [Awesome React Components](https://github.com/brillout/awesome-react-components)
