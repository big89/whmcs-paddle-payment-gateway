For integration with your WHMCS, Contact us : bhagwansahane89@gmail.com

# WHMCS Paddle Payment Gateway

## Summary

Payment Gateway modules allow you to integrate payment solutions with the WHMCS platform.

# Paddle Payment Module for WHMCS

## Installtion Steps

    Download the modules directory or Git clone the modules directory to root directory of WHMCS installtion.
    Upload the module folder into <whmcs_root> directory, and it will be placed <whmcs_root>/modules/gateways/.

## Setup

Begin by activating the payment gateway under Setup > Payments > Payment Gateways and choose Paddle from the Available Gateways dropdown.

# Custom Checkout

Some use-cases require advanced functionality that simply isn’t available via the dashboard. Custom checkouts allow you to access lots of advanced checkout functionality (such as splitting transaction earnings between multiple recipients).

## Custom Checkouts Overview

Custom checkouts allow you to access a plethora of additional checkout functionality that isn’t available via our dashboard by standard.

Custom checkouts can be based on an existing product (in which case they will inherit certain properties of that product - unless you override them) or can be completely custom, and not based on any existing product.

The API will return a link to the checkout that you can pass the user to just like any standard checkout link.

## API Keys

We have two different types of API authentication dependant on where you’re integrating with Paddle. You will see both types referred to in this documentation, we’ve provided a description of each (and where to find them) below.

## Using the Paddle API

If you’re using the Paddle HTTP API (or one of our client libraries), you need to create an ‘auth token’ from within your Paddle account.

To create an auth token, navigate to your ‘Account Settings’ page and click the ‘Integrations’ tab.

Use the ‘Generate API Key’ form at the bottom to create an API key to use with the API. You can revoke these keys at any time and create new ones.

## Using Webhooks

Webhooks are HTTP calls to your server that make it super easy for Paddle to communicate data and events to your server, and for your server to communicate data back.

## Verifying Webhooks

With each webhook (for both Alerts/Events and webhooks used fulfilment) we send a signature field that can be used to verify the webhook was sent by Paddle.

We use public/ private key encryption to allow you to verify these requests. The information below should be a step-by-step guide on how to verify a Paddle signature.


For integration with your WHMCS, Contact us : bhagwansahane89@gmail.com
