ZMQonWin32
==========

Install WAMP and php zmq extension

1. Get wamp installation file on
http://sourceforge.net/projects/wampserver/files/WampServer%202/Wampserver%202.4/Wampserver2.4-x86.exe/download
then install it
2. Download zmq library and php entension from
http://178.79.157.189/~mikko/win32/php-zmq-win32.zip
and extract it
3. Copy /php-zmq/php54/php-zmq_zeromq-3.2.0-zts/php_zmq.dll from the zip files to x:\wamp\bin\php\php5.4.16\ext
4. Copy /php-zmq/libzmq/3.2.0/libzmq.dll from zip files to {WindowsDir}\system32\ or {WindowsDir}\syswow64\
5. Add "extension=php_zmq.dll" to php.ini which WAMP server used, and restart WAMP
Now you can use the ZeroMQ in your PHP project. PS: The other extension files can be downloaded from http://windows.php.net/downloads/pecl/releases/

Wish this is helpful for you.
