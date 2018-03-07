# 3 Musketeers

> RDD, CDD and TDD

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Introduction](#introduction)
- [How to use](#how-to-use)
- [Commands](#commands)
- [Just tell me what to do](#just-tell-me-what-to-do)
  - [RDD and CDD](#rdd-and-cdd)
  - [TDD](#tdd)
- [Licence](#licence)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

* This code is a currency converter ( 32 currency ).
* They are all summed up in currencies.json.
* It uses the API = 'https://api.fixer.io/latest' to stay up to date.

## How to use

* Fork the project via `github`
* Clone your forked repository project `https://github.com/YOUR_USERNAME/3-musketeers`

```sh
❯ cd /path/to/workspace
❯ git clone git@github.com:YOUR_USERNAME/3-musketeers.git
```

* Use the command line :

```sh
❯ ./3-musketeers.git/cash/bitcoin
❯ node index.js
```

## Commands

* Converter

You can convert into mutliple currencies, just add them in <CURRENCY_TO>.

```sh
❯ node index.js <AMOUNT> <CURRENCY_FROM> <CURRENCY_TO>
```
* Save

You can save the currency you use as usual, and the currencies your want to convert it.

```sh
❯ node index.js --save <CURRENCY_FROM> <CURRENCY_TO>
```

* Version

To check the version of 3-musketeers :

```sh
❯ node index.js -v
```
![capture](https://github.com/noxelod/3-musketeers/blob/master/cash/img/cash_converter.png)


## Licence

[Uncopyrighted](http://zenhabits.net/uncopyright/)
