# AppMetrica Push Cordova Plugin

## Documentation
Common documentation available on [AppMetrica official site][DOCUMENTATION].
Documentation for this plugin will be published soon.

## Sample project
Sample project to use is available at [sample/][GitHubSAMPLE].

## Installation
```bash
cordova plugin add yandex-appmetrica-push-plugin-cordova

Android Manifest:
`
            <meta-data android:name="ymp_firebase_default_app_id" android:value="firebase_id" />
            <meta-data android:name="ymp_gcm_default_sender_id" android:value="number:sender_id" />
`
```

It is also possible to install via repo url directly *(not recomended)*:
```bash
cordova plugin add https://github.com/yandexmobile/metrica-push-plugin-cordova.git
```

## Changelog

### Version 0.1.0
* Implemented plugin for AppMetrica Push iOS (v0.5.0) and AppMetrica Push Android (v0.6.1).
* Provided sample.

## License
License agreement on use of Yandex AppMetrica is available at [EULA site][LICENSE]


[LICENSE]: https://yandex.com/legal/appmetrica_sdk_agreement/ "Yandex AppMetrica agreement"
[DOCUMENTATION]: https://tech.yandex.com/appmetrica/doc/mobile-sdk-dg/concepts/about-docpage/ "Yandex AppMetrica documentation"
[GitHubSAMPLE]: https://github.com/yandexmobile/metrica-push-plugin-cordova/tree/master/sample "Sample from reository"
