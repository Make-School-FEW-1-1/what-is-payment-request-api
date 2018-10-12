# Payment Request API

## What is the Payment Request API?
The API was created by the W3C as a potential solution to standardizing payment flow.  The API allows merchants, web sites which sell a service or good, to utilize a single or variety of payment methods with ease and minimal integration.  Via the Payment Request API, the user agent, in this case a browser, will facilitate the payment flow between a merchant and user.

## What does the Payment Request API achieve?
* Allows the browser to work as a middleman among merchants, users, and payment methods
* Provide a large degree of standardization for the payment communication flow
* Implement and support various secure payment methods seamlessly
* Provide universal support to any browser, device, or platform(desktop, mobile, etc.)

## Current support
![browser support](/img/api-support.png)
Payment Request is supports 79.15% of US used user agents and 73.07% of globally used user agents.
***
_Apple has a propietary implementation API named [Apple Pay JS](https://developer.apple.com/reference/applepayjs/). Which has a [wrapper provided by Google](wrapper)._

## Opinions
I think this feature will have tremendous impact on the future of merchant client interactions on the web.  The API has already gained support of many merchants and payment methods, including google pay, stripe, and apple pay.  This will soon see world-wide implementation and be used across the internet in as many ways as possible.  However one of the largest steps between here and there is valuable documentation and dev support.  It was very difficult for me to understand how the API worked and how to use it.

## Demo
To use the demo follow these instruction:

1. Clone the repo: `$git clone git@github.com:Make-School-FEW-1-1/what-is-payment-request-api.git`
1. Open `what-is-payment-request-api/usage-example/credit-card/index.html`
