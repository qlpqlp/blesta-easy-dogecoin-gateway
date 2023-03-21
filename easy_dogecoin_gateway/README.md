# Easy Dogecoin Gateway

This is a placeholder gateway that will present users will instructions for offline payment.

## Install the Gateway

1. You can install the gateway via composer:

    ```
    composer require blesta/easy_dogecoin_gateway
    ```

2. Upload the source code to a /components/easy_dogecoin_gateway/nonmerchant/offline/ directory within
your Blesta installation path.

    For example:

    ```
    /var/www/html/blesta/components/nonmerchant/easy_dogecoin_gateway/
    ```

3. Log in to your admin Blesta account and navigate to
> Settings > Payment Gateways

4. Find the Easy Dogecoin Gateway and click the "Install" button to install it

5. You're done!

### Blesta Compatibility

|Blesta Version|Module Version|
|--------------|--------------|
|< v4.9.0|v1.2.0|
|>= v4.9.0|v1.3.0|
