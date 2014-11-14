#Bookmarklet for Qualys SSL Test

Qualys provide an excellent service for testing a site's SSL / TLS configuration.

This is a quick and dirty bookmarklet that tests the current host, just drag the link below to your bookmarks bar

[Qualys SSL Test]("javascript:(function(){hostname=document.location.hostname;window.open('https://www.ssllabs.com/ssltest/analyze.html?d=' + hostname + '&hideResults=on');})();")

```
javascript:(function(){window.open('https://www.ssllabs.com/ssltest/analyze.html?d=' + document.location.hostname + '&hideResults=on');})();
```
