# Linux shell profile made easy

Effective manage Linux shell profile for sh, bash.

Method:
- create ```profile.d``` dir
- create env file for each application, i.e. ```java_env```
- in ```_env``` file, specify app home dir, add bin dir to PATH
- ```_set_env``` will load env files in this dir
- in ```$HOME/.profile```, source this ```_set_env``` file
- move unused env file to ```.backup```
