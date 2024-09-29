# java_service

```yaml
# Example use
dependencies:
  - role: java_service
    tags: systemd_service
    vars:
      __java_service_name: 'awesome-java-app'
      __java_service_description: 'Awesome Java App as a service'
      __java_service_exec_args: '-jar /some/path/awesome-java-app.jar'
      __java_service_log_file: '/some/path//awesome-java-app.log'
```
