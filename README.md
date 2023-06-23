Импортируйте RuStoreBillingSDKExample.unitypackage в новый проект Unity.

Откройте настройки проекта File -> Edit -> Project Settings -> Player -> Android Settings.
- pаздел Publishing Settings: включите настройки Custom Main Manifest, Custom Main Gradle Template, Custom Gradle Properties Template, настройте keystore для подписи приложения. 
- раздел Other Settings: настройте package name, Minimum API Level = 24, Target API Level = 31 или выше.

Откройте настройки RuStore Billing SDK: Window -> RuStoreSDK -> Settings -> BillingClient. 
- Console Application Id — код приложения из системы RuStore Консоль
- Deeplink Prefix - rustoreunitysdkexample
 
Откройте сцену BillingExampleScene и добавьте идентификаторы продуктов для покупки в список в объекте ExampleController: скрипт Example Controller -> Product Ids. 
