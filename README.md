__LipikaIME__ a user-configurable, phonetic, Input Method Engine for Mac OS X with built-in support for Bengali, Devanagari, Gujarati, Gurmukhi, Hindi, Kannada, Malayalam, Oriya, Tamil and Telugu using ITRANS, Baraha, Harvard Kyoto, Barahavat and Ksharanam transliteration schemes.

> Copyright (C) 2013 Ranganath Atreya

```
This program is free software: you can redistribute it and/or modify it under the terms of the GNU 
General Public License as published by the Free Software Foundation; either version 3 of the License, 
or (at your option) any later version.

This program comes with ABSOLUTELY NO WARRANTY; see LICENSE file.
```

Lipika IME is a many-to-many, user configurable, phonetic, input method engine. Originally, designed to type Sanskrit using Devanagari on a Mac. It can be configured to work with any other Indic language of similar structure.

Installation
------------
To install LipikaIME, follow the **[Installation Instructions](https://github.com/ratreya/Lipika_IME/wiki)**.


#### 05/09/2014: RELEASE NOTES FOR VERSION 1.4 ####
* Highly maintainable proprietary scheme format
* Schemes standerdized for applicability to all Indian languages
  * ITRANS, Baraha, Harvard Kyoto, Barahavat and Ksharanam
  * Minimized exceptions for individual language
* Unicode mapping to all major Indian language scripts
  * Bengali, Devanagari, Gujarati, Gurmukhi, Hindi, Kannada, Malayalam, Oriya, Tamil and Telugu
  * Standerdized naming for consistent transliteration

#### 10/14/2013: RELEASE NOTES FOR VERSION 1.3 ####
* Support for combining fresh typing with existing glyph
* Several bug fixes around candidate window configuration

#### 7/21/2013: RELEASE NOTES FOR VERSION 1.2 ####
* Input Schemes menu now groups schemes by language or rather script
* Added Kannada mappings: Baraha, Barahavat and ITRANS
* Added Telugu mappings: Baraha, Barahavat and ITRANS
* Preferrences greately simplified
  * Input and Output can be displayed or not
  * Input and Output can be displayed either in pop-up window or client
  * Greater font control for pop-up text
  * Ability to choose pop-up panel type

#### 3/31/2013: RELEASE NOTES FOR VERSION 1.1 ####
* Added ability to turn off candidate window
* Echo input text in the client window
* More configuration options for input and candidate text
* Added standard Baraha scheme

#### 3/09/2013: RELEASE NOTES FOR VERSION 1.0 ####
* Ability to configure log level; default is warning
* Configurable backspace behavior: delete mapping, delete ouput
* Configurable onUnfocus behavior: commit inflight, discard inflight, restore inflight onFocus
* Open sourcing the code on github

#### 3/02/2013: RELEASE NOTES FOR VERSION 0.97 ####
* ITRANS version 5.30 using classes for maintainability
* Backspace now deletes single output character at a time
* Various bug fixes including fix for #11

#### 2/25/2013: RELEASE NOTES FOR VERSION 0.95 ####
* Ability to choose from list of available schemes
* User preferences with ability to configure candidate window
* Functionality to automatically persist user preferrences
* Added ITRANS.scm for Indian languages TRANSliteration
* Various bug fixes

#### 2/17/2013: RELEASE NOTES FOR VERSION 0.90 ####
This first release is a minimal credible product with the following features:
  * User configurable IME mapping in Google IME cannonical scheme format.
  * Single candidate in cadidate window showing the current word being worked on.
