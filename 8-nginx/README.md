# PHP-FPM 8

## SMTP Configuration

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Value</th>
      <th>Default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SMTP_SERVER</td>
      <td>IP or Hostname of the SMTP server</td>
      <td><pre>null</pre></td>
    </tr>
    <tr>
      <td>SMTP_PASSWORD</td>
      <td>SMTP Password</td>
      <td><pre>null</pre></td>
    </tr>
    <tr>
      <td>SMTP_USERNAME</td>
      <td>Username</td>
      <td><pre>null</pre></td>
    </tr>
    <tr>
      <td>SMTP_PORT</td>
      <td>smtp port</td>
      <td><pre>null</pre></td>
    </tr>
    <tr>
      <td>PM_STREAM</td>
      <td>Postmark Message Stream ID</td>
      <td><pre>null</pre></td>
    </tr>
         <tr>
      <td>PHP_MAX_CONN</td>
      <td>Maximum number of connections</td>
      <td>35</td>
    </tr>
    <tr>
      <td>PHP_INPUT_VAR</td>
      <td>max_input_vars</td>
      <td>3000</td>
    </tr>
    <tr>
      <td>PHP_MEMORY_LIMIT</td>
      <td>memory_limit</td>
      <td>192M</td>
    </tr>
    <tr>
      <td>PHP_UPLOAD_SIZE</td>
      <td>upload_max_filesize</td>
      <td>250M</td>
    </tr>
    <tr>
      <td>PHP_INPUT_TIME</td>
      <td>max_input_time</td>
      <td>300</td>
    </tr>
    <tr>
      <td>PHP_EXEC_TIME</td>
      <td>max_execution_time</td>
      <td>300</td>
    </tr>
    <tr>
      <td>PHP_TIMEZONE</td>
      <td>date.timezone</td>
      <td>UTC</td>
    </tr>
    <tr>
      <td>PHP_POST_SIZE</td>
      <td>post_max_size</td>
      <td>250M</td>
    </tr>
    <tr>
      <td>PHP_OPCACHE</td>
      <td>opcache.enable</td>
      <td>1</td>
    </tr>
    <tr>
      <td>PHP_ERROR_REPORTING</td>
      <td>error_reporting</td>
      <td>E_ALL & ~E_DEPRECATED & ~E_STRICT</td>
    </tr>
    <tr>
      <td>PHP_DISPLAY_ERRORS</td>
      <td>display_errors</td>
      <td>Off</td>
    </tr>
    <tr>
      <td>PHP_LOG_ERRORS</td>
      <td>log_errors</td>
      <td>On</td>
    </tr>
  </tbody>
</table>

## Monarx Support

This image includes support for [Monarx](https://www.monarx.com). By default it's _**disabled**_ unless you include the following environmental variables at boot (_can be enabled after initial install_):

* `MONARX_ID`
* `MONARX_SECRET`