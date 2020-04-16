**Installing and cloning manually**

Clone and configure the sample yourself:

```
git clone https://github.com/langhamerm/StripeAPI.git
```

Create a .env file in the server folder and paste the following:

```
# Stripe API keys - see https://stripe.com/docs/development#api-keys
STRIPE_PUBLISHABLE_KEY=pk_test
STRIPE_SECRET_KEY=sk_test

#Environment setup (web client)
STATIC_DIR=../../client/web

```

You will need a Stripe account in order to run the demo. Once you set up your account, go to the Stripe [developer dashboard](https://stripe.com/docs/development#api-keys) to find your API keys.

```
STRIPE_PUBLISHABLE_KEY=<replace-with-your-publishable-key>
STRIPE_SECRET_KEY=<replace-with-your-secret-key>
```

`STATIC_DIR` tells the server where the client files are located and does not need to be modified unless you move the server files.

**2. Follow the server instructions on how to run:**

Pick the server language you want and follow the instructions in the server folder README on how to run.

Run the following in your terminal:

```
cd server/node then run:

npm install
npm start

```
**3. Test the Integration**

There are several test cards you can use in test mode to make sure this integration is ready. Use them with any CVC, postal code, and future expiration date.

TEST CARD NUMBERS:

4242424242424242

4000002500003155

4000000000009995
