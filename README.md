[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://spdx.org/licenses/0BSD.html)
[![GitHub Issues](https://img.shields.io/github/issues/Kronos-Integration/interceptor-line-tokenizer-csv.svg?style=flat-square)](https://github.com/Kronos-Integration/interceptor-line-tokenizer-csv/issues)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FKronos-Integration%2Finterceptor-line-tokenizer-csv%2Fbadge\&style=flat)](https://actions-badge.atrox.dev/Kronos-Integration/interceptor-line-tokenizer-csv/goto)
[![Styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Known Vulnerabilities](https://snyk.io/test/github/Kronos-Integration/interceptor-line-tokenizer-csv/badge.svg)](https://snyk.io/test/github/Kronos-Integration/interceptor-line-tokenizer-csv)
[![Coverage Status](https://coveralls.io/repos/Kronos-Integration/interceptor-line-tokenizer-csv/badge.svg)](https://coveralls.io/github/Kronos-Integration/interceptor-line-tokenizer-csv)

# @kronos-integration/interceptor-line-tokenizer-csv

Splits a line by a sparator into tokens

# API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [LineTokenizerInterceptor](#linetokenizerinterceptor)
*   [stream](#stream)
*   [constructor](#constructor)
    *   [Parameters](#parameters)
*   [\_transform](#_transform)
    *   [Parameters](#parameters-1)

## LineTokenizerInterceptor

**Extends Interceptor**

This interceptor cares about the handling of the messages.
It will add the hops and copies the messages

## stream

This module reads an object stream which contains a string data field.
It will split this string into tokens

## constructor

Creates the line tokenizer and sets the options.
The following options are supported:
{
"separator\_list" : \[',', ';'],
"quote\_char" : '"',
"use\_quotes" : true,
"trim" : true
}

### Parameters

*   `opts` &#x20;

## \_transform

Reads the stream data and split it into lines.

### Parameters

*   `data` &#x20;
*   `enc` &#x20;
*   `cb` &#x20;

# install

With [npm](http://npmjs.org) do:

```shell
npm install @kronos-integration/interceptor-line-tokenizer-csv
```

# license

BSD-2-Clause
