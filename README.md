# px-typeahead [![Build Status](https://travis-ci.org/predixdesignsystem/px-typeahead.svg?branch=master)](https://travis-ci.org/predixdesignsystem/px-typeahead)


## Overview

`Px-typeahead` is a Predix UI component similar to a dropdown which shows possible autocompletion options for a given search term based on a list of possible values.

## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm, and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

## Getting Started

First, install the component via bower on the command line:

```
bower install px-typeahead --save
```

Second, import the component in your application with the following tag in your head:

```
<link rel="import" href="/bower_components/px-typeahead/px-typeahead.html"/>
```

Finally, use the component in your application:

```
<px-typeahead max-suggestions="10" local-candidates="{{your-array-of-input-strings}}" placeholder="your-placeholder">
</px-typeahead>
```

<br />
<hr />

## Documentation

Read the full API and view the demo [here](https://www.predix-ui.com/#/elements/px-typeahead).

The documentation in this repository is supplemental to the official Predix documentation, which is continuously updated and maintained by the Predix documentation team. Go to [http://predix.io](http://predix.io)  to see the official Predix documentation.


## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.


### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues]( https://github.com/predixdesignsystem/px-typeahead/issues) to submit any bugs you might find.
