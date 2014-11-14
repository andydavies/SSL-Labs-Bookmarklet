#Bookmarklet for Qualys SSL Test

Qualys provide an excellent service for testing a site's SSL / TLS configuration.

This is a quick and dirty bookmarklet that tests the current host, just drag the link below to your bookmarks bar

<a href="javascript:(function(){hostname=document.location.hostname;window.open('https://www.ssllabs.com/ssltest/analyze.html?d=' + hostname + '&hideResults=on');})();">Qualys SSL Test</a>

```
javascript:(function(){window.open('https://www.ssllabs.com/ssltest/analyze.html?d=' + document.location.hostname + '&hideResults=on');})();
```
