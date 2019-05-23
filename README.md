# MKRFOX 1200 - Retrieve board informations

Use this sketch to retrieve your Arduino [MKRFOX](https://www.arduino.cc/en/Main.ArduinoBoardMKRFox1200) board ID & PAC, to register online in 3 minutes through the Sigfox DevKit [onboarding platform](http://buy.sigfox.com/activate).

This sketch does not send any message over the Sigfox network. It only retrieve identity information from the ATA8520 chipset.

⚠️ The PAC provided by the board is the factory value. It's a throw-away value and can only be used once, for initial registration. 
If you want to forward ownership of the board, you will need to contact the [Sigfox support](http://support.sigfox.com) to get your up-to-date PAC.


