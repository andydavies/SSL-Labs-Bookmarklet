#Bookmarklet for Qualys SSL Test

Qualys provide an excellent service for testing a site's SSL / TLS configuration.

This is a quick and dirty bookmarklet that tests the current host, just create a bookmarklet with the contents below

```
javascript:(function(){window.open('https://www.ssllabs.com/ssltest/analyze.html?d=' + document.location.hostname + '&hideResults=on');})();
```

Only tested on Chrome
