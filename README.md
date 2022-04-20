# MMM-PIR-Sensor

username: '', // Sign up for free using the OneTracker App
password: '',
useHeader: true, // false if you don't want a header
header: 'My Packages', // Change in config file. useHeader must be true
maxWidth: '300px',
animationSpeed: 3000, // fade speed
initialLoadDelay: 3250,
retryDelay: 2500,
updateInterval: 10 * 60 * 1000, // 10 minutes
apiLanguage: 'en',
maxParcels: 5,

<table width="100%">
  <thead>
    <tr>
      <th>Property</th>
      <th width="100%">Description</th>
    </tr>
  <thead>
  <tbody>
    <tr>
      <td><code>usename</code></td>
      <td>The username/email address of the OneTracker account.
        <br><b>Required</b>
      </td>
    </tr>
    <tr>
      <td><code>password</code></td>
      <td>The password of the OneTracker account.
        <br><b>Required</b>
      </td>
    </tr>
    <tr>
      <td><code>useHeader</code></td>
      <td>Display a header on top of the module
        <br><b>Default:</b> <code>true</code> 
      </td>
    </tr>
    <tr>
      <td><code>header</code></td>
      <td>The header to use (if <code>useHeader</code> is set to <code>true</code>.
        <br><b>Optional:</b>
      </td>
    </tr>
    <tr>
      <td><code>retryDelay</code></td>
      <td>The delay before retry if connection issus.
        <br><b>Default:</b> <code>2500</code>
      </td>
    </tr>
    <tr>
      <td><code>updateInterval</code></td>
      <td>The interval between updates (in millisecond).
        <br><b>Default:</b> <code>10*60*1000</code> (10 minutes)
      </td>
    </tr>
    <tr>
      <td><code>maxParcels</code></td>
      <td>The maximum number of parcel to display.
        <br><b>Default:</b> <code>5</code>
      </td>
    </tr>
  </tbody>
</table>