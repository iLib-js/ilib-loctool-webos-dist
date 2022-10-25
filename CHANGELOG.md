## 1.9.0
* Updated fixed loctool and plugins version
* Added the utility function to override language default locale.
* Added new getTranslations() method on the Project calss to get all of the translations.
* Fixes in plugins
  * (webos-c/webos-cpp) Updated to support loctool's generate mode.
  * (webos-javascript/webos-c/webos-cpp/webos-ts-resource/webos-appinfo-json) Added ability to override language default locale.
  * (webos-javascript) Updated generate mode to use loctool's new public method.
~~~
    "ilib-loctool-webos-appinfo-json": "1.3.0",
    "ilib-loctool-webos-c": "1.2.0",
    "ilib-loctool-webos-cpp": "1.2.0",
    "ilib-loctool-webos-javascript": "1.5.0",
    "ilib-loctool-webos-json-resource": "1.4.0",
    "ilib-loctool-webos-qml": "1.3.7",
    "ilib-loctool-webos-ts-resource": "1.3.0",
    "loctool": "2.18.0"
~~~

## 1.8.0
* Updated fixed loctool and plugins version
* Fixes in plugins
  * (webos-appinfo-json) Fixed not to generate duplicated resource by comparing language default locale translation.
  * (webos-c/webos-cpp) Fixed an issue where strings are not extracted due to incorrect deletion of commented lines.
  * (webos-javascript/webos-c/webos-cpp) Updated to check language default locale translation not to generate duplicate resources.
  * (webos-javascript) Updated to make source and key policy clear to avoid confusion.
  * (webos-json-resource) Removed source and target comparison code when generating resources.
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.12",
    "ilib-loctool-webos-c": "1.1.7",
    "ilib-loctool-webos-cpp": "1.1.7",
    "ilib-loctool-webos-javascript": "1.4.7",
    "ilib-loctool-webos-json-resource": "1.3.11",
    "ilib-loctool-webos-qml": "1.3.6",
    "ilib-loctool-webos-ts-resource": "1.2.10",
    "loctool": "2.17.0"
~~~

## 1.7.0
* Updated fixed loctool and plugins version 
* Used the logger provided by the loctool instead of using log4js directly.
* Fixes in plugins
  * (webos-javascript) Fixed an issue where the $L(key, value) usage could not be parsed properly.
  * (webos-json-resource) Fixed not to generate an empty directory if the content is empty even locale is in the target list.
  * (webos-appinfo-json) Fixed to set base locale correctly when calculating resource path.
  * (webos-qml) Added js to the list of file extensions that this plugin handles.
  * (webos-qml) Fixed an issue not to filter newline characters for a window.

~~~
    "ilib-loctool-webos-appinfo-json": "1.2.11",
    "ilib-loctool-webos-c": "1.1.6",
    "ilib-loctool-webos-cpp": "1.1.6",
    "ilib-loctool-webos-javascript": "1.4.6",
    "ilib-loctool-webos-json-resource": "1.3.10",
    "ilib-loctool-webos-qml": "1.3.5",
    "ilib-loctool-webos-ts-resource": "1.2.9",
    "loctool": "2.16.3"
~~~


## 1.6.0
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.10",
    "ilib-loctool-webos-c": "1.1.5",
    "ilib-loctool-webos-cpp": "1.1.5",
    "ilib-loctool-webos-javascript": "1.4.5",
    "ilib-loctool-webos-json-resource": "1.3.9",
    "ilib-loctool-webos-qml": "1.3.4",
    "ilib-loctool-webos-ts-resource": "1.2.8",
    "loctool": "2.16.2"
~~~

## 1.5.0
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.9",
    "ilib-loctool-webos-c": "1.1.4",
    "ilib-loctool-webos-cpp": "1.1.4",
    "ilib-loctool-webos-javascript": "1.4.4",
    "ilib-loctool-webos-json-resource": "1.3.8",
    "ilib-loctool-webos-qml": "1.3.3",
    "ilib-loctool-webos-ts-resource": "1.2.7",
    "loctool": "2.14.1"
~~~

## 1.4.0
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.8",
    "ilib-loctool-webos-c": "1.1.3",
    "ilib-loctool-webos-cpp": "1.1.3",
    "ilib-loctool-webos-javascript": "1.4.3",
    "ilib-loctool-webos-json-resource": "1.3.7",
    "ilib-loctool-webos-qml": "1.3.2",
    "ilib-loctool-webos-ts-resource": "1.2.6",
    "loctool": "2.13.0"
~~~

## 1.3.0
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.7",
    "ilib-loctool-webos-c": "1.1.2",
    "ilib-loctool-webos-cpp": "1.1.2",
    "ilib-loctool-webos-javascript": "1.4.2",
    "ilib-loctool-webos-json-resource": "1.3.6",
    "ilib-loctool-webos-qml": "1.3.1",
    "ilib-loctool-webos-ts-resource": "1.2.5",
    "loctool": "2.12.0"
~~~

## 1.2.3
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.6",
    "ilib-loctool-webos-c": "1.1.1",
    "ilib-loctool-webos-cpp": "1.1.1",
    "ilib-loctool-webos-javascript": "1.4.1",
    "ilib-loctool-webos-json-resource": "1.3.5",
    "ilib-loctool-webos-qml": "1.3.0",
    "ilib-loctool-webos-ts-resource": "1.2.4",
    "loctool": "2.10.3"
~~~


## 1.2.2
* Updated fixed plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.5",
    "ilib-loctool-webos-c": "1.1.0",
    "ilib-loctool-webos-cpp": "1.1.0",
    "ilib-loctool-webos-javascript": "1.4.0",
    "ilib-loctool-webos-json-resource": "1.3.4",
    "ilib-loctool-webos-qml": "1.2.0",
    "ilib-loctool-webos-ts-resource": "1.2.3",
    "loctool": "2.10.2"
~~~

## 1.2.1
* Updated fixed plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.4",
    "ilib-loctool-webos-json-resource": "1.3.3",
    "ilib-loctool-webos-ts-resource": "1.2.2"
~~~

## 1.2.0
* Updated fixed loctool and plugins version
~~~
    "ilib-loctool-webos-appinfo-json": "1.2.2",
    "ilib-loctool-webos-c": "1.0.1",
    "ilib-loctool-webos-cpp": "1.0.1",
    "ilib-loctool-webos-javascript": "1.3.0",
    "ilib-loctool-webos-json-resource": "1.3.2",
    "ilib-loctool-webos-qml": "1.1.1",
    "ilib-loctool-webos-ts-resource": "1.2.1",
    "loctool": "2.10.0"
~~~

## 1.0.0
* Release v1.0.0 for webOS OSE

## 0.0.3
* Removed node_modules directory. then Changed to be installed packages by running `npm install` during a webOS build.

## 0.0.2
* Updated `ilib-loctool-webos-appinfo-json` version to `1.2.1`

## 0.0.1
* Initial Commit
