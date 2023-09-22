# Credit Card Entry

This xApp lets the user enter credit card information.

The following data is sent to the `{{input.data}}` object:

```json
{ 
    "_cognigy": {
      "_app": {
        "type": "submit",
        "payload": {
          "name": "sdf sdf",
          "cardnumber": "5356 5920 4530 5948",
          "expirationdate": "11/25",
          "securitycode": "333"
        }
      }
    }
}
```

