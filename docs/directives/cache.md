# $[cache]
Saves a value temporarily to be used in other commands

Fetch values from the cache using the [cache variable](</variables/cache>). The cache is not meant to be used as a long term or permanent place to store any sensitive or important information. This cache could be reset at any time without warning.

## Usage
$[cache `<key>` `<seconds>` `<value>`]

## Example
    $[cache $(username) 60 some value to save for later] value saved

Saves "some value to save for later" to the cache for 60 seconds

`!cache` -> `value saved`