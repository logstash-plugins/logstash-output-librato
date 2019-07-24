## 3.0.7
  - Fix formatting in doc for conversion to --asciidoctor [#tbd](https://github.com/logstash-plugins/logstash-output-librato/pull/tbd)

## 3.0.6
  - Docs: Set the default_codec doc attribute.

## 3.0.5
  - Update gemspec summary

## 3.0.4
  - Fix some documentation issues

# 3.0.3
  - Docs: Add plugin description
# 3.0.2
  - Docs: Fix plugin ID
# 3.0.1
  - Docs: Update doc example to use new event API syntax 
# 3.0.0
  - Update plugin to the new event API
# 2.0.4
  - Depend on logstash-core-plugin-api instead of logstash-core, removing the need to mass update plugins on major releases of logstash
# 2.0.3
  - New dependency requirements for logstash-core for the 5.0 release
## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully, 
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0

