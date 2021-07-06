# Ippopay Flutter SDK Integration

## Step - 1 - Add Dependency

We distribute our SDK from the Flutter's pub.dev Repository. To begin with this SDK open your pubspec.yaml file and
add the following dependency.

```

dependencies:
  ippo_pay: ^0.0.2
```

## Step - 2 - Install SDK 

To install the SDK add the below line of code.

```
$ flutter pub get
```

## Step - 3 - Import SDK 

Now in your Dart code, import the following line.

```
import 'package:ippo_pay/ippo_pay.dart';
```

## Step - 4 - Import Android SDK Dependency 

Now open Android Studio and open android/app/build.gradle file. Paste the following line of code. Once done, Sync the project to get the library installed.

```
implementation 'com.ippopay:IppoPaySDK:2.0.4'
```

## Step - 5 - Now you just need to follow the steps given in the below sample to integrate the remaining.

Please check [this link](https://pub.dev/packages/ippo_pay/example) for sample payment with above steps.

