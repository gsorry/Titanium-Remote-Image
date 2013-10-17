This is simple Titanium module for creating image view for displaying remote images.
It works on iOS as well as on Android platform.
Current version does not support caching, should be in future versions.

Example:
 ```javascript
var RemoteImage = require('lib/RemoteImage');

var remoteImage = RemoteImage.createImageView({
    image: 'http://www.yoursite.com/sample_image.jpg',
    height: 100,
    width: 100,
    onload: function() {
        // this is optional callback function
    },
});
 ```
