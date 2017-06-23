# Easy Moonscript Guide
A quick and easy way of understanding moonscript

## General overview
expand on -> moonscript is just coffeescript for lua

## Tup and Build System
* what is Tup
* go-to commands and directory structures

## Language Idioms
* [check out how lua guide does this section](https://docs.google.com/presentation/d/1AxiCAxSnGiicg1c1IU54sDaseAQA9CLFbhoIRdsd1Rw/edit#slide=id.g219f327ff2_0_189)

## Lapis
* what is lapis
* ez lapis structure
** lapis new --tup
** touch config.moon
```
-- config.moon
config = require "lapis.config"

config "development", ->
  port 8080

config "production", ->
  port 80
  num_workers 4
  code_cache "on"
```
