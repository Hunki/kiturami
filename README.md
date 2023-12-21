* source from https://github.com/stkang/home-assistant-custom-component

## 귀뚜라미 IOT 보일러
``` yaml
climate:
  - platform: kiturami
    name: kiturami
    username: !secret default_username
    password: !secret default_password
    scan_interval: 1800
```
