# Elasticsearch Using Url output plugin for Embulk
This plugin is forked from https://github.com/ipros-team/embulk-output-elasticsearch_ruby

## Overview

* **Plugin type**: output
* **Load all or nothing**: no
* **Resume supported**: no
* **Cleanup supported**: yes

## Configuration

## Example

```yaml
out:
  type: elasticsearch_using_url
  mode: normal
  nodes:
    - url: "http://localhost:9200"
```


## Build

```
$ rake
```
