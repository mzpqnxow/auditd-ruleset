# auditd-ruleset
This is an auditd based ruleset for carefully monitoring user accounts. Useful when ensuring that service accounts aren't being used interactively, for example a `www-data` type user

# How to handle log output

Take a look at [audisp-json](https://github.com/gdestuynder/audisp-json) and consider streaming into logstash

## Quick guide to setting up audisp-json

Just look at all of the files in the repository, they are placed as they would need to be if on a system. And of course, build and install audisp-json ...
