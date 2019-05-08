sms-calculator
=============================
Simple library to help calculate the number of SMS corresponding to a certain text content.


### [Demo](https://codepen.io/thedoctor46super/full/qGOYLg){:target="_blank"}


Usage
----------

```javascript
SMSCalculator.getCount('📱Some really awesome SMS content 🔥')
```

This will return the following object:

```javascript
{
  maxCharCount: 70,
  numberOfSMS: 1,
  remaining: 34,
  totalLength: 36
}
```
