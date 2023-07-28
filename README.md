# ansible-role-win-updates

Role to install Windows Updates

## Table of content

- [Default Variables](#default-variables)
  - [win_updates_category_names](#win_updates_category_names)
  - [win_updates_enabled](#win_updates_enabled)
  - [win_updates_install](#win_updates_install)
  - [win_updates_reboot](#win_updates_reboot)
  - [win_updates_reboot_timeout](#win_updates_reboot_timeout)
  - [win_updates_skip_optional](#win_updates_skip_optional)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### win_updates_category_names

Windows Update category names The value * will match all categories

#### Default value

```YAML
win_updates_category_names:
  - CriticalUpdates
  - SecurityUpdates
  - UpdateRollups
```

### win_updates_enabled

Enable/disable Windows Updates Service

#### Default value

```YAML
win_updates_enabled: true
```

### win_updates_install

Install updates

#### Default value

```YAML
win_updates_install: true
```

### win_updates_reboot

Reboot automatically during updates

#### Default value

```YAML
win_updates_reboot: yes
```

### win_updates_reboot_timeout

#### Default value

```YAML
win_updates_reboot_timeout: 5400
```

### win_updates_skip_optional

Skip optional updates

#### Default value

```YAML
win_updates_skip_optional: false
```



## Dependencies

None.

## License

license (GPLv2, CC-BY, etc)

## Author

andif888
