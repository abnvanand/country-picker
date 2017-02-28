# country-picker
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/anandAbhi/country-picker)

A polymer element to select country code/dial code.

## Installation
bower install anandAbhi/country-picker

## Usage 
 see _demo/index.html_
```
<template is="dom-bind">
    <button onclick="picker.open()">Select country</button>
    <p>[[country.dialCode]] [[country.name]]</p>
    <country-picker id="picker"
            country="{{country}}">
    </country-picker>
</template>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D