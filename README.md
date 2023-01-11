# Tinder-Deblur
Simple script using the official Tinder API to get clean photos of the users who liked you.
------------------------------------------------------------------------------------------------
How to use: 

install a userscript manager (Violentmonkey, Tampermonkey, Greasemonkey, ...)
------------------------------------------------------------------------------------------------
install the script:

either click this link and the manager will install the script for you
or copy the URL below and install it manually through manager's UI
https://raw.githubusercontent.com/tajnymag/tinder-deblur/main/tinder.user.js
browse the Tinder web app normally and the profiles that like you should be unblurred
------------------------------------------------------------------------------------------------
How does it work
Initially, Tinder API returned clean profile images on requests that had their headers stripped down. Recently Tinder patched this exploit for the web app. However, they did not patch it for their Android API. So that's what this script is using now.
------------------------------------------------------------------------------------------------
