# Hostinghelden Magento2 Extension Bundle

removes not used extension from core and adds following extension to your installation:

* [Hostinghelden/Smtp](https://github.com/dni/hostinghelden-smtp)
* [Hostinghelden/Pdf](https://github.com/dni/hostinghelden-pdf)
* [Hostinghelden/Pdfupload](https://github.com/dni/hostinghelden-pdfupload)

# Requirements

Magento Composer Installer: To copy the module contents under app/code/ folder. In order to install it run the below command on the root directory:

```sh
composer require magento/magento-composer-installer
```

Add the VCS repository: So that composer can find the module. Add the following lines in your composer.json

```json
  "repositories": {
    "0": {
      type: composer,
      url: https://repo.magento.com
    },
    "hostinghelden": {
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
