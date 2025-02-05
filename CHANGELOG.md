# Changelog

## 2.0.2 (2022-03-23)
 * Using orjson instead of simplejson or other serializers for speed benefit
 * Fix: Output decimal.Decimal as int or float not str

## 2.0.1 (2021-11-23)
  * Fixed an issue when `format_message` returned newline character

## 2.0.0 (2021-11-23)
  * Swith to `orjson` JSON library to serialie and deserialise faster
  * Bump `backoff` to 1.11.1
  * Bump `pytz` to latest

## 1.3.0 (2021-08-12)
  * Added `time_extracted` to BATCH message type

## 1.2.0 (2020-12-01)
  * Add BATCH message type

## 1.1.4 (2020-11-05)
  * Update pytz pin to wider range

## 1.1.3 (2020-06-11)
  * Bump jsonschema to 3.2.0

## 1.1.2 (2020-04-29)
  * Bump pytz to 2020.1

## 1.1.1 (2020-03-19)
  * Bump pytz to 2019.3

## 1.1.0 (2020-02-17)
  * Added a logging config file to fallback to in case LOGGING_CONF_FILE env variable is not defined. This is to 
  respect the singer specs that requires the logs to be sent to stderr and not stdout.

## 1.0.0 (2020-02-06)
  * Initial version (fork of https://github.com/singer-io/singer-python version 5.9.0)
