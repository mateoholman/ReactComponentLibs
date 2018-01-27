# Choosing a React Component Library

Component libraries allow you to speed up UI development.
They often enforce development approaches and best practices.
They minimize decision fatigue.
They allow you to ship an MVP / product faster.
They help keep your code readable and maintainable.

Choosing a library will depend on what you need.
There are a shitton of options out there.

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
* Size:
* Maintainers: Javi Velasco | Javi Jiménez | Community
* License: MIT

## React MD
As you might’ve guessed, the “MD” in “React-MD” stands for “Material Design”. This library is almost two years old, and it’s 99% a one-man project pushed forward by Mikkel Laursen.

In spite of this fact, React-MD looks surprisingly good. As a matter of fact, the smooth animations and the sheer speed of its documentation/live demonstration website puts Semantic UI to shame. Besides, React MD lets you access 40 high-quality components styled with SASS, beating the component count of many of its competitors.

* Current version:
* Contributors:
* GitHub Stars:
* Open bugs / issues:
* Size:
* Maintainers:  | Community
* License:

## React MDL
## React-materialize
## React-material
## React-essence

---

# Bootstrap

## React-Bootstrap
The idea of building UIs with both Bootstrap and React might be tempting, but the combo is too messy to write on your own. Luckily, some folks are already doing it for you, and their project is gaining traction.

React-Bootstrap was pioneered by Matthew Honnibal, Stephen J. Collings, and Pieter Vanderwerff. The project is in active development, and it already offers a smart implementation of Bootstrap 3 styling encapsulated into React components. It allows you to create and modify such components using JS objects or JSX without having to worry about potential abstraction issues.

## Reactstrap

## Pivitol-ui-react
---

## Ant Design
Ant Design is way more that just a React library or framework. It’s a massive (and somewhat enclosing) ecosystem with a proprietary style guide, custom Webpack-based build tool and custom CLI applications. The project is really well-polished, with giants like Alibaba and Baidu using it.

On the overall, Ant Design would look really neat if it weren’t for one gotcha: most of the documentation, PRs and discussions are in Chinese. The React components library, on the other hand, has English documentation. Besides, the impressive assortment of 50+ React components really makes the case for Ant Design.

## Blueprint
Blueprint is a component library with a primary focus on building data-heavy interfaces for desktop screens. Being essentially desktop-first, it doesn’t offer much in the way of mobile UIs, which is an important thing to consider. One distinguishing feature of Blueprint is that it’s a TypeScript-based React library.

## Semantic UI
This library promises a clean React-friendly implementation of Semantic UI with its minimalist out-of-the-box styling. The original vision behind Semantic UI comes down to the use of standard React components that developers can modify and expand.

## Fabric
The official React components library from Microsoft, Fabric brings the aesthetic of Ms Office to third-party web apps. Much like Material Design, Fabric is a complete design language rather than a collection of “starter-pack” styles that you will heavily modify.

One tricky thing with the library is the licensing of the fonts and brand icons. While the library itself is MIT-licensed, the fonts and brand icons from MSFT aren’t. This means they might be out of reach if you’re working on an independent project, which seems like a downer.

## Grommet
Grommet makes a great first impression thanks to its neat documentation, style guide, and its huge number of available UI components. Furthermore, it offers a solid enterprise-grade solution complete with a full-fledged design language.

Being a project of Hewlett Packard, Grommet reflects the company’s vision of UX best practices, which might feel a little too specific. In fact, developers claim the framework’s component structuring is somewhat restrictive, with certain components only accepting certain children, nested in a certain way.

## Rebass
Rebas might seem like another “work-in-progress” library, yet its Github page demonstrates recent major contributions. Rebass uses styled components and enables developers to implement architecture patterns based on the separation of concerns between presentational and container components.

A peculiar thing about Rebass is that it only includes presentational UI components. This approach leaves you writing container components to handle application logic and higher-level architecture, but it also allows for greater flexibility.

## React Desktop
React Desktop is different from other libraries on this list because it’s essentially a small collection of Windows and macOS UI elements.

Specifically, we’re talking about 19 macOS and 10 windows components mimicking native UI elements of the two operational systems.

## React Belle
## Material Components Web
## Onsen UI
## React-foundation-apps
## React-foundation
## Aframe-react
## admin-on-rest

# Khan Academy


## Resources

* [Devarchy](https://devarchy.com/react/topic/ui-framework)
* [Awesome React Components](https://github.com/brillout/awesome-react-components)
