# Magento 2 Disable Right Click Extension

## Introduction
The **Magento 2 Disable Right Click Extension** helps protect your store's content by preventing users from right-clicking, copying text, or inspecting the page source. This extension enhances content security and prevents unauthorized access to your store's data and images. By using this extension, you can safeguard your store from plagiarism and content theft while improving user experience.

## How It Works
The **Magento 2 Disable Right Click Extension** seamlessly integrates into your Magento 2 store, restricting users from performing right-click, copying content, or inspecting elements. This feature ensures your store's proprietary content remains secure. Additionally, it prevents unwanted access to HTML source code, reducing the risk of data breaches or unauthorized modifications.

## Key Features
- Restrict right-click functionality on all store pages.
- Disable text selection and copy-paste actions.
- Prevent users from inspecting the store's source code.
- Lightweight and easy-to-configure extension.

## Disable Right Click Feature
This feature blocks users from right-clicking on your store, preventing them from accessing context menus, inspecting elements, or copying images and text.

## Text Selection & Copy Prevention
The extension disables text selection and copying, ensuring your store's product descriptions, blog content, and other text remain protected from unauthorized duplication.

## Source Code Protection
By preventing users from inspecting your store's HTML source code, this feature helps safeguard critical design elements and scripts from unauthorized use.

## Lightweight & Easy Configuration
With a simple installation and intuitive admin settings, this extension is lightweight and does not affect the store's performance, making it an ideal solution for content security.

## Extension Installation
To install the **Magento 2 Disable Right Click Extension**, follow these steps:

### Step 1: Install the extension using Composer:
```bash
composer require vendor/disable-right-click
```
For a specific version:
```bash
composer require vendor/disable-right-click:version
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following Magento commands:
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 Disable Right Click Extension
### Step 1 - Navigate to Admin Panel
Go to **Stores > Configuration > CodeDecorator > Disable Right Click**.

### Step 2 - Enable/Disable Right Click Block
Enable or disable the restriction based on your store requirements.

### Step 3 - Save Configuration
Click on the **Save Config** button and clear the cache to apply changes.

## Download Our [Magento 2 Disable Right Click](https://codedecorator.com/magento-2-disable-right-click.html) Extension
