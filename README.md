SSL Certificate Checker Cordova Plugin
Description
Enhance the security of your mobile app by preventing 'Man in the Middle' attacks. This plugin adds an extra layer of protection by allowing you to verify the SSL certificate of your server through fingerprint comparison. This makes it challenging for hackers to intercept communication between your app and your server.

You can choose to check the connection when the app starts or invoke the plugin every time you communicate with the server. Customize the logic within success and error callbacks to suit your application's needs.

This version is compatible with PhoneGap 3.0 and higher.
For PhoneGap 2.9 and lower, refer to the pre-phonegap-3 tree.
Supports Cordova Plugman.
Officially supported by PhoneGap Build

Installation
Install the latest stable version from npm:

$ cordova plugin add cordova-plugin-sslcertificatechecker
For the bleeding edge version from GitHub:

$ cordova plugin add https://github.com/Adeshinadesola/SSLCertificateChecker
PhoneGap Build
Refer to the Usage section for detailed instructions on using the plugin.
Need SSL Pinning?
If manual certificate checking isn't sufficient and you want to ensure each HTTPS request is secure, consider using the Secure HTTP plugin.
Cert Chain Checking
Up until version 4.0.0, this plugin provided chain checking through the checkInCertChain property. However, for increased security, this feature has been removed. If you require chain checking without pinning, use an older version of the plugin.

