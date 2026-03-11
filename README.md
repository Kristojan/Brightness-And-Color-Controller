# Brightness Controller

This is a fork of version 2.4 of Brightness Controller for Linux. It supports two displays and also allows changing the color temperature across displays in all language system.

To generate new .ts type  files with your language, your can do it:
  - From /brightness-controller-linux/brightness_controller_linux/ui :
```bash
lupdate . -ts brightness-controller_ll-LL.ts
```
ll_LL is the abbreviation for your country's language (example: de_DE for deutchland, en_US for north Aaerica, etc...) 
  - Translate with Qt Linguist:
```bash
linguist brighness-controller_ll-LL.ts
```
  - Generate .qm type file:
```bash
lrelease brighness-controller_ll-LL.ts
```
To finalize people must generate a type .deb package wirh locale translation standard, or other builds...


