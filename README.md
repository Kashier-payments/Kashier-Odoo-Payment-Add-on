# Kashier-Odoo-Payment-Add-on
Kashier payment gateway support for Odoo 16


![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/odoo-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for egyptian merchants.

- IFrame Integration.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.

- Support multiple payment methods
     
     - card 
     - wallet
     - bank installments

- Customize order state after success payment.

### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/kashier_payment.zip)

- unzip the downloaded file and Add the Addon to your odoo server in the location `Odoo 16.0 > server > odoo > addons` or in the `custom_addon` location.

- Restart your odoo server.

- Update Your apps list.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/update_apps_list.png)

- Install Kashier Payment Add on.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/kashier_addon_install.png)

- Enable and Configure your kashier Addon by navigating `Invoicing > Configuration > Payments > Payment Aquirers`.

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > Payment API keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-15-Payment-Add-on/main/steps/apikey_mid_test.png)

- Insert the Merchant Id and Test Api Key in the Configuration page of the Kashier Add on.

- Make sure the test mode is on.

- Make sure that you select Payment Journal of type Bank Also Add Supported Payment Icon.

- Customize the name of the payment method.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/module_configuration_plus.png)

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/module_configuration_test.png)

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added "Kashier Online Payment". it could be changed from Addon configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/module_test_payment_1.png)

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/module_test_payment_2.png)

### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > Payment API Keys

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/apikey_mid_live.png)

- Insert Live Payment Api Key in the Configuration page of the Kashier Payment Addon.

- Enable Live mode.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Odoo-Payment-Add-on/v16/steps/module_configuration_live.png)

### Notes

- Leave us an inquiry ticket on https://kashier.io for questions.
