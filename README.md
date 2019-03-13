# Testing --- Demos for Generic Sensor API

----

## [Sensor Info demo](https://ronhere.github.io/generic-sensor-demos/sensor-info/build/bundled/) ([code](https://github.com/ronhere/generic-sensor-demos/tree/master/sensor-info/build/bundled))

This web application presents information about device sensors and their reading values.

**Note:** this demo requires
[chrome://flags/#enable-generic-sensor-extra-classes](chrome://flags/#enable-generic-sensor-extra-classes)
flag set.

<img width="40%" src="sensor-info/sensor-info.gif?raw=true" alt="Sensor Info demo">

---

### Development environment

If you would like to modify the existing code and experiment with the sensors API
your code must be hosted on a web server that supports HTTPS.
The simplest way is to fork this repository and enable
[GitHub Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)
for your fork. Alternatevely, you can serve your web application locally, for this, we recommend to use
[Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb).
If you are developing for mobile devices,set up
[port forwarding](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/local-server)
for your local server, and you are good to go!

### Reporting a security issue
If you have information about a security issue or vulnerability with an Intel-maintained open source project on https://github.com/intel, please send an e-mail to secure-opensource@intel.com. Encrypt sensitive information using our PGP public key. For issues related to Intel products, please visit https://security-center.intel.com.
