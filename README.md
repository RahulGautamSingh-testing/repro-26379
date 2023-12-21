# Debug Logs

```log
DEBUG: Parsing configs
DEBUG: Checking for config file in C:\Users\Acer\Desktop\renovate/config.js
 WARN: Found warnings in the config file C:\Users\Acer\Desktop\renovate/config.js
       "warnings": [
         {
           "topic": "Deprecation Warning",
           "message": "Direct editing of prTitle is now deprecated. Please edit commitMessage subcomponents instead as they will be passed through to prTitle."
         }
       ]
DEBUG: env RENOVATE_CONFIG
       "envRC": "{\"enabled\":\"invalid-value\"}"
DEBUG: Detected config in env RENOVATE_CONFIG
       "config": {"enabled": "invalid-value"}
 WARN: Found errors in the config RENOVATE_CONFIG
       "errors": [
         {
           "topic": "Configuration Error",
           "message": "Configuration option `enabled` should be boolean. Found: \"invalid-value\" (string)"
         }
       ]
DEBUG: File config
       "config": {
         "repositoryCache": "disabled",
         "token": "***********",
         "repositories": ["RahulGautamSingh-testing/repro-26379"],
         "prTitle": "something"
       }
DEBUG: CLI config
       "config": {}
DEBUG: Env config
       "config": {"enabled": "invalid-value", "hostRules": []}
DEBUG: Combined config
       "config": {
         "repositoryCache": "disabled",
         "token": "***********",
         "repositories": ["RahulGautamSingh-testing/repro-26379"],
         "prTitle": "something",
         "enabled": "invalid-value",
         "hostRules": []
       }
```
