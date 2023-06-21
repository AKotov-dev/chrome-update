# chrome-update
**Dependencies:** urpmi

Checking for updates to the `google-chrome-stable` package is performed daily, but no more than 1 time a day 5 minutes after the computer boots. Files are being created:
```
/etc/chrome-update/chrome-update
/etc/systemd/system/chrome-update.service
```
**Note:** The initial installation of the browser is done from the [developer's website](https://www.google.com/intl/ru_ru/chrome/).
  
Tested in Mageia-8/9.
