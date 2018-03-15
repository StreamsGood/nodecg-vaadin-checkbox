# nodecg-vaadin-checkbox

[![Greenkeeper badge](https://badges.greenkeeper.io/StreamsGood/nodecg-vaadin-checkbox.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/StreamsGood/nodecg-vaadin-checkbox.svg?branch=master)](https://travis-ci.org/StreamsGood/nodecg-vaadin-checkbox)

```sh
bower install StreamsGood/nodecg-vaadin-checkbox --save
```

Extends [`vaadin-checkbox`](https://vaadin.com/elements/vaadin-checkbox/) to add NodeCG replicant support.
* `replicant-name`: The identifier for the replicant.
* `replicant-bundle`: Optional. Defaults to the active bundle.

```html
<nodecg-vaadin-checkbox replicant-name="name" replicant-bundle="bundle"></nodecg-vaadin-checkbox>
```

For a full list of supported attributes, see the [`vaadin-checkbox`](https://vaadin.com/elements/vaadin-checkbox/) documentation.

---

**Note:** This does not specify styling for vaadin-elements, you will need to install and include either the `vaadin-material-theme` or `vaadin-valo-theme` yourself.

```sh
bower install vaadin/vaadin-material-theme --save
```

```html
<link rel="import" href="bower_components/vaadin-material-theme/vaadin-checkbox.html">
```