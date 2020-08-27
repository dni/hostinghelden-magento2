# Hostinghelden Magento2 Extension Bundle

adds following extension to your installation:

* Hostinghelden/Smtp
* Hostinghelden/Pdfupload

# Requirements

Magento Composer Installer: To copy the module contents under app/code/ folder. In order to install it run the below command on the root directory:

```sh
composer require magento/magento-composer-installer
```

Add the VCS repository: So that composer can find the module. Add the following lines in your composer.json

```json
  "repositories": {
    "magento2": {
      "type": "vcs",
      "url": "https://github.com/dni/hostinghelden-magento2"
    },
    "pdfupload": {
      "type": "vcs",
      "url": "https://github.com/dni/hostinghelden-pdfupload"
    },
    "pdf": {
      "type": "vcs",
      "url": "https://github.com/dni/hostinghelden-pdf"
    },
    "smtp": {
      "type": "vcs",
      "url": "https://github.com/dni/hostinghelden-smtp"
    }
  },
```

# Installation

Add the module to composer:

```sh
composer require hostinghelden/hostinghelden-magento2
```
