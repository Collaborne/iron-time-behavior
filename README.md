_[Demo and API Docs](http://collaborne.github.io/iron-time-behavior)_


iron-time-behavior [![Bower version](https://badge.fury.io/bo/iron-time-behavior.svg)](http://badge.fury.io/bo/iron-time-behavior) [![Travis state](https://travis-ci.org/Collaborne/iron-time-behavior.svg?branch=master)](https://travis-ci.org/Collaborne/iron-time-behavior)
=========

Polymer 1.x behavior that provides time-from-now string, e.g. today, yesterday, this week, earlier.

The element builds on the [momentjs](http://momentjs.com) library.

To use this element:

`bower install iron-time-behavior`


## i18n Support

`iron-time-behavior` uses [Moment.js](http://momentjs.com), and so supports all locales that Moment.js supports. But,
the component does not reference any specific locale, so when you want to use it with a locale other than `en` you must
load the locales explicitly.

~~~~
<link rel="import" href="bower_components/iron-time-behavior/iron-time-behavior.html">
<script src="bower_components/moment/min/locales.js"></script>
~~~~

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
