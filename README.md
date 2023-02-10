# Selenium_2fa
## Automation of two factor authentication for [Steam](https://store.steampowered.com/) with help of [Outlook](https://outlook.live.com/) using Selenium

### Test Data:
The test method fetches test data using System.getProperty() add following arguments in your run configuration
...
-Doutlook_username=your outlook email
-Doutlook_password=your outlook password
-Dsteam_username=your steam username
-Dsteam_password=your steam password
...

### Note:
Steam account should be created using an Outlook email for the automation to work as intended
