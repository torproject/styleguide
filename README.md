# Style Guide

The Tor Styleguide is based on [Bootstrap](https://getbootstrap.com/), an open-source toolkit for developing with HTML, CSS, and JS. We are currently [implementing v4.0.0-beta.2](https://github.com/twbs/bootstrap/releases/tag/v4.0.0-beta.2). 

You can also clone this repository and use our CSS or SASS files. SASS is a CSS extension language. Bootstrap and this styleguide are based on v3.5.4.

If you want to use SASS you can download the complete archive for the styleguide. The scss folder under assets contains all the sass files. Since we use bootstrap, we only add a few styles without modifying bootstrap core or defining new elements whenever possible. These are _tor_variables.scss and _tor.scss. These are imported in the main bootstrap scss file and compiled into the final css.

## About 

Bootstrap contains a few JavaScript libraries for extra interaction with the DOM. We use these libraries but do not add extra JavaScript. You might notice that if you run Tor Browser with high security mode, JavaScript is disabled by default. This styleguide is designed to also work for users using Tor Browser in high security mode, so that only few elements are affected if you disable JavaScript.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine. This styleguide has been built using [Lektor](https://www.getlektor.com/). Lektor is a static content management system. You can build this yourself by installing Lektor.


### Prerequisites

What things you need to install the software 
- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [lektor](https://www.getlektor.com/docs/installation/)

### Installing

Get the code by running:
```
git clone [repo address]
```

You must run two commands to pull the submodule:

```
git submodule init 
```
then

```
git submodule update
```


### Run/Build With

```
lektor server
```


## Extras

We also provide a minimal Lektor template website that you can start modifying. This is available at this [repository](https://gitweb.torproject.org/project/web/template.git/).
