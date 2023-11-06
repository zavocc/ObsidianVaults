My OPPO A5 2020 device configuration with debloated/disabled apps. (Oct 31 2023)

The aim is to reduce attack surface/intrusive services as possible, providing clean user experience without ads from App market and other heytap cloud related services baked into the device.

With careful research how Android framework and apps work together, I combined multiple sources and biases to synthesize what is safe to disable or not, I even developed an OCD choosing stability or extremeness of batshit user privacy and reliability against ColorOS apps.

**Sources for packages that is safe to disable:**
- [UAD Lists (raw)](https://raw.githubusercontent.com/0x192/universal-android-debloater/main/resources/assets/uad_lists.json)
	Notably to search for \*oppo* \*realme* \*nearme* \*heytap* \*oplus* packages
	
	The [Universal Android Debloater](https://github.com/0x192/universal-android-debloater) is a great tool to discover what apps are safe to uninstall based on their functionality, but since ColorOS is just as diverse ever since OnePlus + Oppo merged, not all things are listed but it had its equivalents (e.g. com.coloros !== com.oplus packages, e.g. com.oplus.athena which is com.coloros.athena)
- [Realme UI 2.0 & 3.0 Debloat config from reddit](https://www.reddit.com/r/Realme/comments/w12bbk/realme_rui_20_rui_30_debloat_list/)
- [Why Xiaomi replaced its AOSP-based system dialer with Google ones](https://xiaomiui.net/why-has-xiaomi-replaced-some-of-the-miui-phone-apps-with-google-apps-28446/)
- [Safe to remove stock dialer and contacts with ADB?](https://xdaforums.com/t/safe-to-remove-stock-dialer-and-contacts-with-adb.3738514/)
- [How to remove phone+contacts from stock LineageOS?](https://www.reddit.com/r/LineageOS/comments/an2emy/how_to_remove_phonecontacts_from_stock_los/)
- [Uninstall Realme bloatware](https://forum.xda-developers.com/t/uninstall-realme-bloatware.4308103/)
### Uninstalled Apps
How to fully immobilize apps:
`pm uninstall --user 0 <package.name>`

Restore apps:
`pm install-existing <package.name>`

> [!NOTE] Uninstalled Apps
> com.caf.fmradio
com.coloros.activation
com.coloros.assistantscreen
com.coloros.backuprestore
com.coloros.compass2
com.coloros.floatassistant
com.coloros.gamespace
com.coloros.healthcheck
com.coloros.logkit
com.coloros.musiclink
com.coloros.phonemanager
com.coloros.phonenoareainquire
com.coloros.providers.downloads.ui
com.coloros.sceneservice
com.coloros.securitykeyboard
com.coloros.smartdrive
com.coloros.smartsidebar
com.coloros.video
com.coloros.weather2
com.coloros.wifibackuprestore
com.facebook.appmanager
com.facebook.services
com.facebook.system
com.google.android.permissioncontroller.overlay.oppo
com.heytap.cast
com.heytap.cloud
com.heytap.colorfulengine
com.heytap.datamigration
com.heytap.market
com.heytap.mcs
com.heytap.music
com.heytap.openid
com.heytap.pictorial
com.heytap.themestore
com.nearme.atlas
com.nearme.statistics.rom
com.oplus.crashbox
com.oppo.lfeh
com.oppo.operationManual
com.oppo.oppopowermonitor
com.oppo.quicksearchbox
com.oppo.usercenter
com.oppoex.afterservice
com.redteamobile.roaming
com.tencent.soter.soterserver
com.wapi.wapicertmanage
### Disabled Apps
How to disable apps:
`pm disable-user <package.name>`

Enable:
`pm enable <package.name>`

> [!NOTE] Disabled Apps
> com.android.mms
com.coloros.alarmclock
com.coloros.calculator
com.coloros.securepay
com.coloros.weather.service
com.oppo.camera
com.qualcomm.atfwd


