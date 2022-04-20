# MMM-PIR-Sensor


| Option           | Type  | Description
|----------------- |----------- |-----------
| `url` | *Required* | The url or IP address for the OctoPrint server
| `api_key` | *Required* | Your API Key from the OctoPrint server
| `printerName` | *Optional* | Add a name to show on top of the module
| `showStream` | *Optional* | Whether or not to show the camera stream. **Default:** `true`
| `maxStreamWidth` | *Optional* | Maximum width for stream display in pixels (`0` for stream width). **Default:** `0`
| `maxStreamHeight` | *Optional* | Maximum height for stream display in pixels (`0` for stream height). **Default:** `0`
| `streamUrl` | *Optional* | Set a custom url for accessing the camera stream. **Default**: `url:8080/?action=stream`
| `showTemps` | *Optional* | Whether or not so show temperature info. **Default:** `true`
| `showDetailsWhenOffline` | *Optional* | Whether or not to hide the printer details when the printer is offline. **Default:** `false`
| `interactive` | *Optional* | Allow interactive control of the printer. **Default:** `true`.
