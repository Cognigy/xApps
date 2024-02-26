# Take Photo

This xApp lets the user take a photo:

<img src="./docs/example1.png" width="200">
<img src="./docs/example2.png" width="200">

As soon as this xApp is opened by the user's device, they are asked to allow the camera if not available already. After taking the photo, the following information is sent to the Cognigy.AI Flow:

```json
{
 "data": {
    "_cognigy": {
      "_app": {
        "type": "submit",
        "payload": {
          "image": "data:image/png;base64,iVBORw0KGgoAAA..."
        }
      }
    }
 }
}
```

As the image might be too big to be displayed directly, it is recommended to store the file in an external data storage for further usage.