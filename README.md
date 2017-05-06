# [unicode-json](https://github.com/Zertz/unicode-json) [![Build Status](https://travis-ci.org/Zertz/unicode-json.svg?branch=master)](https://travis-ci.org/Zertz/unicode-json) [![NPM version](https://badge.fury.io/js/unicode-json.png)](http://badge.fury.io/js/unicode-json)

[![Greenkeeper badge](https://badges.greenkeeper.io/blakeembrey/unicode-json.svg)](https://greenkeeper.io/)

> Downloads http://unicode.org/Public/UNIDATA/UnicodeData.txt and saves each category into a JSON file.

## Install

```
npm install unicode-json
```

If you got the file already at hand you can specify the path to it in the environment variable `NODE_UNICODETABLE_UNICODEDATA_TXT`.

## Usage

```
> require('unicode/category/So')["♥".charCodeAt(0)]
{ value: '2665',
  name: 'BLACK HEART SUIT',
  category: 'So',
  class: '0',
  bidirectional_category: 'ON',
  mapping: '',
  decimal_digit_value: '',
  digit_value: '',
  numeric_value: '',
  mirrored: 'N',
  unicode_name: '',
  comment: '',
  uppercase_mapping: '',
  lowercase_mapping: '',
  titlecase_mapping: '',
  symbol: '♥' }
```
