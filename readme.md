oneschema
=========

## Purpose

The purpose of `oneschema` is to define a common, root ground truth for an application's datamodel from which API's, structs, and database DDL code can be generated.

## XML

`oneschema` is defined in `XSD`, thus `oneschema` documents are `XML` documents. `XSD` is a schema definition language in itself, but `XSD` is too deep and powerful for what we want to do. We want to define a much smaller implementation surface for `oneschema` so we are creating smaller schema definition language, which itself is defined in `XSD`.

## History

  * April 27, 2019 - initial commit