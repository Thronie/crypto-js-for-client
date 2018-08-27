# crypto-js-for-client
Crypto js for react, react-native, angular.

1. Download crypto.js file and save in your project folder.

`import crypto from './crypto';`
or
`const crypto = require('./crypto');

    const secret = 'open-sesame';
    const hash = crypto.createHmac('sha256', secret)
                   .update('abcdefg')
                   .digest('hex');`
                   
Create Hmac or Certificate in clients.
