# Message-Encoder
Message-Encoder is a lite option to encode messages into images and decode them back.

### Useage
Open Message-Encoders HTML file in a webbrowser and click on the **"Encode"** tab. Then uplpload a image (jpg, png), you will see a before preview below, type the message to be encoded and click the **"Encode"** button to hide the message. You will see a Normalized view and the encoded image, to save the image right click > save as.

### For Devlopers
**_see license.txt_**

JavaScript on release will be encoded, download from [Main Page](https://github.com/CarsonDS/Message-Encoder/tree/script)

**DO NOT CHANGE** click functions:
```
$('button.encode, button.decode').click(function(event) {
  event.preventDefault();
});
```

**Message-Encoder is _NOT 100% SECURE_**
