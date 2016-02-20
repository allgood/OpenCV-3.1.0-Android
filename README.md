OpenCV 3.1.0 for Android
========================

This project is a gradle compatible import of the original java classes from OpenCV for Android.

It can be imported by gradle on any Android project through jitpack.io.

On the build.gradle of your application.

Add jitpack.io on the repositories section, you may need to keep another lines:

```
    maven { url "https://jitpack.io" }
```

Then on the dependencies section you need to reference this library:

```
    compile 'com.github.ctodobom:OpenCV-3.1.0-Android:-SNAPSHOT'
```

After this, ```org.opencv.*``` packages will be availeble for import.


Donations
---------

My job is on enterprise servers administration and some development consulting. I do collect money from my customers. I am well paid for that.

For being part of open source projects and documenting my work here I really do not charge anything. I am trying to avoid any type of ads also.

If you think that any information you obtained here is worth of some money and are willing to pay for it, feel free to send any amount through paypal or bitcoin.

| Paypal | Bitcoin |
| ------ | ------- |
| [![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=X6XHVCPMRQEL4) | <center> ![1H5tqKZoWdqkR54PGe9w67EzBnLXHBFmt9](http://todobom.com/images/bitcoin-donations.png)<br />1H5tqKZoWdqkR54PGe9w67EzBnLXHBFmt9</center> |

License
-------

OpenCV is released through a [3 clause BSD License](http://opencv.org/license.html)
