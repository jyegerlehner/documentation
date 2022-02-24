.. _lan-mac:

==========================
Trusting Embassy CA on Mac
==========================

#. Locate your Embassy's Root CA, right click, then click *Open with > Keychain Access*.

    .. figure:: /_static/images/ssl/embassy_lan_setup1.png
        :width: 60%
        :alt: LAN setup prompt

#. Enter your computer password when prompted. It will be imported into your mac's keychain.

    .. figure:: /_static/images/ssl/macos/certificate_untrusted.png
        :width: 60%
        :alt: Keychain access import menu

    .. note:: If the keychain console did not open, press "Command + spacebar" and type “Keychain Access”, and hit enter to open it.

#. Navigate to the "System" tab on the left, find the certificate named "Embassy Local Root CA", and double click on this certificate. A second window will pop up.

#. Open the "Trust" dropdown and select "Always Trust" from the dropdown next to "When using this certificate".

    .. figure:: /_static/images/ssl/macos/always_trust.png
        :width: 60%
        :alt: Keychain submenu

#. Close this window and enter your password to apply the settings.

#. The "Embassy Local Root CA" cert will now read "This certificate is marked as trusted for all users" in Keychain Access.

    .. figure:: /_static/images/ssl/macos/certificate_trusted.png
        :width: 60%
        :alt: Keychain menu trusted certificate
