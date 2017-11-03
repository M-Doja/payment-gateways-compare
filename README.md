# payment-gateways-compare

Compare three payment gateways (PayPal, Stripe, Braintree) in developer aspect. This project built using Node-ExpressJS as well as the NodeJS SDKs from three vendors.

This repo hosts the source codes which described in this [Blog post](https://blog.simonho.net/paypal-vs-braintree-vs-stripe-ux-sdk/)

## Run the project

### 1. Enter your payment gateway access keys
In project root, create a text file `.env` and fill in the accesskey values from your payment processors.
```yaml
PAYPAL_MODE=[sandbox|production]
PAYPAL_ACCOUNT_EMAIL=[classic paypal account email]
PAYPAL_CLIENT_ID='[Your PayPal Client Id]'
PAYPAL_CLIENT_SECRET='[Your PayPal Client Secret]'

BT_ENVIRONMENT=[Sandbox|Production]
BT_MERCHANT_ID='[Your Braintree Merchant ID]'
BT_PUBLIC_KEY='[Your Braintree public key]'
BT_PRIVATE_KEY='[Your Braintree private key]'

STRIPE_PUBLISH_KEY='[Your Stripe pubishable key]'
STRIPE_SECRET_KEY='[Your Stripe secret key]'
```

### 2. Server App Installation
```sh
npm install
```

### 3. Run the server App
```sh
npm start
```

### 4. Browse the server
Open your Chrome browser and browse: http://localhost:3000

# App Execution Description
Please refer to the [Blog post](https://blog.simonho.net/paypal-vs-braintree-vs-stripe-ux-sdk/)
