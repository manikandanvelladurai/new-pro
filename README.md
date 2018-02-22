<?xml version='1.0' encoding='utf-8'?>
<widget id="com.sics.jk" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">
    <name>JK</name>
      <description>An awesome Ionic/Cordova app.</description>
    <author email="hi@ionicframework" href="http://ionicframework.com/">Ionic Framework Team</author>
    <content src="index.html" />
    <access origin="*" />
    <allow-navigation href="http://ionic.local/*" />
    <allow-intent href="http://*/*" />
    <allow-intent href="https://*/*" />
    <allow-intent href="tel:*" />
    <allow-intent href="sms:*" />
    <allow-intent href="mailto:*" />
    <allow-intent href="geo:*" />
    <preference name="webviewbounce" value="false" />
    <preference name="UIWebViewBounce" value="false" />
    <preference name="DisallowOverscroll" value="true" />
    <preference name="android-minSdkVersion" value="16" />
    <preference name="BackupWebStorage" value="none" />
    <preference name="SplashMaintainAspectRatio" value="true" />
    <preference name="FadeSplashScreenDuration" value="300" />
    <preference name="SplashShowOnlyFirstTime" value="false" />
    <preference name="SplashScreen" value="screen" />
    <preference name="SplashScreenDelay" value="3000" />
    <platform name="android">
        <allow-intent href="market:*" />
        <icon density="ldpi" src="resources/android/icon/drawable-ldpi-icon.png" />
        <icon density="mdpi" src="resources/android/icon/drawable-mdpi-icon.png" />
        <icon density="hdpi" src="resources/android/icon/drawable-hdpi-icon.png" />
        <icon density="xhdpi" src="resources/android/icon/drawable-xhdpi-icon.png" />
        <icon density="xxhdpi" src="resources/android/icon/drawable-xxhdpi-icon.png" />
        <icon density="xxxhdpi" src="resources/android/icon/drawable-xxxhdpi-icon.png" />
        <splash density="land-ldpi" src="resources/android/splash/drawable-land-ldpi-screen.png" />
        <splash density="land-mdpi" src="resources/android/splash/drawable-land-mdpi-screen.png" />
        <splash density="land-hdpi" src="resources/android/splash/drawable-land-hdpi-screen.png" />
        <splash density="land-xhdpi" src="resources/android/splash/drawable-land-xhdpi-screen.png" />
        <splash density="land-xxhdpi" src="resources/android/splash/drawable-land-xxhdpi-screen.png" />
        <splash density="land-xxxhdpi" src="resources/android/splash/drawable-land-xxxhdpi-screen.png" />
        <splash density="port-ldpi" src="resources/android/splash/drawable-ldpi-screen.png" />
        <splash density="port-mdpi" src="resources/android/splash/drawable-mdpi-screen.png" />
        <splash density="port-hdpi" src="resources/android/splash/drawable-hdpi-screen.png" />
        <splash density="port-xhdpi" src="resources/android/splash/drawable-xhdpi-screen.png" />
        <splash density="port-xxhdpi" src="resources/android/splash/drawable-xxhdpi-screen.png" />
        <splash density="port-xxxhdpi" src="resources/android/splash/drawable-xxxhdpi-screen.png" />
     
    </platform>
    <platform name="ios">
        <allow-intent href="itms:*" />
        <allow-intent href="itms-apps:*" />
        <icon height="57" src="resources/ios/icons/icon.png" width="57" />
        <icon height="114" src="resources/ios/icons/icon@2x.png" width="114" />
        <icon height="40" src="resources/ios/icon/icon-40.png" width="40" />
        <icon height="80" src="resources/ios/icon/icon-40@2x.png" width="80" />
        <icon height="120" src="resources/ios/icon/icon-40@3x.png" width="120" />
        <icon height="50" src="resources/ios/icon/icon-50.png" width="50" />
        <icon height="100" src="resources/ios/icon/icon-50@2x.png" width="100" />
        <icon height="60" src="resources/ios/icon/icon-60.png" width="60" />
        <icon height="120" src="resources/ios/icon/icon-60@2x.png" width="120" />
        <icon height="180" src="resources/ios/icon/icon-60@3x.png" width="180" />
        <icon height="72" src="resources/ios/icon/icon-72.png" width="72" />
        <icon height="144" src="resources/ios/icon/icon-72@2x.png" width="144" />
        <icon height="76" src="resources/ios/icon/icon-76.png" width="76" />
        <icon height="152" src="resources/ios/icon/icon-76@2x.png" width="152" />
        <icon height="167" src="resources/ios/icon/icon-83.5@2x.png" width="167" />
        <icon height="29" src="resources/ios/icon/icon-small.png" width="29" />
        <icon height="58" src="resources/ios/icon/icon-small@2x.png" width="58" />
        <icon height="87" src="resources/ios/icon/icon-small@3x.png" width="87" />
        <splash height="1136" src="resources/ios/splash/Default-568h@2x~iphone.png" width="640" />
        <splash height="1334" src="resources/ios/splash/Default-667h.png" width="750" />
        <splash height="2208" src="resources/ios/splash/Default-736h.png" width="1242" />
        <splash height="1242" src="resources/ios/splash/Default-Landscape-736h.png" width="2208" />
        <splash height="1536" src="resources/ios/splash/Default-Landscape@2x~ipad.png" width="2048" />
        <splash height="2048" src="resources/ios/splash/Default-Landscape@~ipadpro.png" width="2732" />
        <splash height="768" src="resources/ios/splash/Default-Landscape~ipad.png" width="1024" />
        <splash height="2048" src="resources/ios/splash/Default-Portrait@2x~ipad.png" width="1536" />
        <splash height="2732" src="resources/ios/splash/Default-Portrait@~ipadpro.png" width="2048" />
        <splash height="1024" src="resources/ios/splash/Default-Portrait~ipad.png" width="768" />
        <splash height="960" src="resources/ios/splash/Default@2x~iphone.png" width="640" />
        <splash height="480" src="resources/ios/splash/Default~iphone.png" width="320" />
    </platform>
    <engine name="android" spec="^6.2.3" />
    <plugin name="cordova-plugin-console" spec="1.0.5" />
    <plugin name="cordova-plugin-device" spec="1.1.4" />
    <plugin name="cordova-plugin-geolocation" spec="^2.4.3" />
    <plugin name="cordova-plugin-splashscreen" spec="~4.0.1" />
    <plugin name="cordova-plugin-statusbar" spec="2.2.2" />
    <plugin name="cordova-plugin-whitelist" spec="1.3.1" />
    <plugin name="ionic-plugin-deploy" spec="^0.6.7" />
    <plugin name="ionic-plugin-keyboard" spec="~2.2.1" />
      <plugin name="mx.ferreyra.callnumber" spec="~0.0.2" />
    <plugin name="cordova-plugin-nativestorage" spec="^2.2.2" />
    <plugin name="uk.co.workingedge.phonegap.plugin.launchnavigator" spec="^4.1.3" />
    <plugin name="cordova-plugin-geolocation" spec="~2.4.3" />
    <plugin name="cordova-plugin-nativegeocoder" spec="^3.0.0" />
    <plugin name="cordova-sqlite-storage" spec="1.2.1" />
    <plugin name="de.appplant.cordova.plugin.local-notification" spec="0.8.2" />
    <plugin name="cordova-plugin-background-mode" spec="^0.7.2" />
    <plugin name="cordova-plugin-splashscreen" spec="^4.0.3" />
    <plugin name="cordova-plugin-x-socialsharing" spec="^5.2.1" />
 
</widget>
