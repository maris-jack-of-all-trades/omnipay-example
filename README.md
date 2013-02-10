# Tala Payments: Example Application

This is an example web application built using the [Silex](http://silex.sensiolabs.org/)
micro-framework. It demonstrates using Tala Payments to process payments using all supported
payment gateways.

## Getting Started

To run the example application, you must first install the development dependencies via composer.
From the root `tala-payments` directory, run:

    composer update --dev

You can the use the built in web server (PHP 5.4+) to start the application:

    php -S localhost:8000 -t example/

The application will now be available at http://localhost:8000/

## Configuration

To test a gateway, you will need to have access to valid credentials. To obtain valid credentials,
contact the payment gateway's support.

You can configure a gateways settings in the application. All data is stored using regular PHP
sessions, so will not be persisted between sessions.
