# Signature

This xApp lets the user upload a picture:

<img src="./docs/example.png" width="200">

The user can upload a picture from their device, such as a smartphone, and submit it to be sent to Cognigy.AI. In this case, the following data is sent to the `{{input.data}}` object:

```json
{
  "data": {
    "_cognigy": {
      "_app": {
        "type": "submit",
        "payload": {
          "picture": "data:image/png;base64,iVBO..."
        }
      }
    }
  }
}
```

The picture, which is sent as base64 image to `{{input.data._cognigy._app.payload.picture}}` can be displayed with a Say Node or stored in antoher system -- for example.