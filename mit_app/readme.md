## Andriod app built in MIT App Inventor
<br>

__Created using the [MIT App Inventor platform](https://iot.appinventor.mit.edu/), with some vibe coding here and there.__
<br>

- Searches for BLE devices and shows list
- User can choose between manual Mastago controls or ButtPlug IntiFace connection.
- App loads JS Websocket code into a WebCanvas window with the JS code, intefacing with ButtPlug Intiface.
- ButtPlug VIBRATION levels are translated to TENS intensity level.
- Pattern is set within app to 19
- buzz buzz
<br>

<br>

___Working___
- Mastago BT services are mapped out
- TENS Manual controls work for Start/Stop, Pattern, Intensity
- Data is sent between BT device and Intiface
- VIBRATION is translated to TENS intensity level
<br>

___To Do___
- Figure out a good KeepAlive method. Intiface expects a real Websocket PING that the JS code cannot create. Testing constant DEVICE responses to see if connection stays up. Might not be needed if data is flowing constantly.
- Send battery strength to Intiface
- Increase remaining TENS activation time
- Allow changes to Intiface IP address from localhost
<br>

___Future possibilities___
- Change pattern type depending on Funscript rythms
- Show more device info on app screen
<br>

<br>

## MIT App Code
_Coming soon!!_
<br>

<br>

## JS websocket Code
js_websockets.html
<br>

<br>

## MIT App Modules
__BLE extension for MIT APP Inventor__ \
_edu.mit.appinventor.ble_ \
https://iot.appinventor.mit.edu/iot/reference/bluetoothle
<br>

<br>

### The following modules _might_ work for a similar project.
_Sourced from Websocket extensions for MIT APP Inventor_ \
https://community.appinventor.mit.edu/t/all-rescued-extensions-from-inactive-communities/27169/26  
<br>

<br>

__Andres Cotes - meh__ \
_com.gmail.at.moicjarod.aix_ \
https://community.appinventor.mit.edu/t/tcp-ip-extension/7142/41 \
<br>

__Jean-Rodolphe_Letert - seems to be a TCP socket with websocket abilities??__ \
_co.com.dendritas.WebSocketCl.aix_ \
https://web.archive.org/web/20190926062820/https://community.appybuilder.com/t/websocket-client-extension/1761
