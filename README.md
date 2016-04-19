# katapult-qr
A Polymer element that scans and decodes QR Codes

# Installation
Install with bower: `bower install KatapultDevelopment/katapult-qr`

# Use

Add the element to your page and it will fill its parent container. You can start and stop the live scanning by
calling the `startScanning()` and `stopScanning()` methods.  Scanning will not be on by default, so you need to start
it manually when ready.  The `data` property is set when new data is decoded from a QR code, and a `success` event will
be called when the `data` property is set.

# Example

`<katapult-qr data="{{decodedData}}" on-success="successCallback"><katapult-qr>`
