node-validate-email
===================

There are a lot of email validators out there; let's raise the bar a bit on quality.  MIT licensed.





Wossis then?
------------

I mean, it's exactly what it sounds like.  This is an email address validator.  Right now this is a clone of someone else's validator; the intent is to provide a point to be upgraded with time.

This library comes with a [shootout](https://github.com/StoneCypher/node-validate-email-shootout) to display which library does the best job for which validation.

The goal of this library is to provide RFC-5322 compliant validation.  At this time, the author is unaware of a validator library which achieves the 60% valid mark against an admittedly borderline silly list of corner cases.  However, the validator also fails certain common cases currently; donations are encouraged.





How do I shot web?
------------------

Pretty straightforward.  Install the library, either with `npm install node-validate-email --save` or your mechanism of preference.  Then, in your code:

```javascript
var validator    = require('node-validate-email'),
    isBillGValid = validator('billg@microsoft.com'),
    validAsText  = isBillGValid? 'yes' : 'no';

window.alert('Is billg@microsoft.com a valid email? ' + validAsText);
```

Piece of cake.





Polemic :neckbeard:
-------------------

`node-validate-email` is MIT licensed, because viral licenses and newspeak language modification are evil.  Free is ***only*** free when it's free for everyone.
