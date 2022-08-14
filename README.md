# Actecnology TransShipping for Magento 2

## How to install & upgrade Actecnology_TransShipping

### 1. Install
#### 1 Install

```
copiar a  Actecnology/TransShipping
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

### 2. Copy and paste

If you want you can use this way. 

- Extract `master.zip` file to `app/code/Actecnology/TransShipping` ; You should create a folder path `app/code/Actecnology/TransShipping` if not exist.
- Go to Magento root folder and run upgrade command line to install `Actecnology_TransShipping`:

```
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```
