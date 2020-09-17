# Changelog

## 0.4.0 - 2020-06-02
* fixes
  * fix key_value join character to space
  * fix dummy dependency alerts
* features
  * add new const MESSAGE_FORMATS and test for checking the value of message_format
  * add check message_format
  * boolean flag replace with a whitelist and create method for generating a message
  * added ability to log messages format k=v

## 0.3.1 - 2020-04-21
* fixes
  * fix error "modify frozen String" for class name in helpers

## 0.3.0 - 2020-04-17
* fixes
  * make public #generate_log_transaction_id in helper
  * removed incoming http modifier

## 0.2.0 - 2020-04-13
* fixes
  * fix Readme with active_record modifier
  * fix except option for helper #log_options
  * refactor helpers #log_type
  * fix helper define log_methods caller
  * improve stability of helpers
* features
  * remove legacy agent from default log pattern
  * new active record modifier
  * improve sidekiq modifier for difference versions