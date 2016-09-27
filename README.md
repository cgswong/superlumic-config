# superlumic-config

This is the default configuration "role" for [Superlumic](https://github.com/superlumic/superlumic). You will want
to fork this one and modify "default.yml" to your liking. Alternatively, you can create additional YAML files to suite your specific needs. Use the roles folder to create "profiles".

How you organize your config files is entirely up to you, but this is how I do it. The "profile-all" role are the apps and settings that
everyone in my company needs. Then I have a group file per type of installation (developers, designers, etc). In specific "username.yml"
playbook I then add all the specific things for the corresponding users (with "default.yml" being a reference for what a default user might want).
