# Build an offline first cross-platform web and mobile apps with Flutter and AWS Amplify


## Pre-requisites

- [Install Flutter](https://docs.flutter.dev/get-started/install)
- [Install AWS Amplify CLI](https://docs.amplify.aws/cli/start/install/#install-the-amplify-cli)
- [Install Android Studio](https://developer.android.com/studio?gclid=Cj0KCQjw5-WRBhCKARIsAAId9FkBunOt81NLUOrVgkdsNvEnzcFDFaqCWppt6ASiBZOs_KJx1V2u0sYaArIuEALw_wcB&gclsrc=aw.ds)
- [Install IOS Emulator](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

## Steps

### Clone the repository 
- git clone https://github.com/jeeri2204/flutter_jeerid.git
- cd flutter_jeerid

### Install the necessary packages
- flutter pub get

### Initialize AWS Amplify
- amplify init

### Add AWS Amplify DataStore Feature
- amplify api add

### Add AWS Amplify Authentication Feature
- amplify auth add

### Add AWS Amplify Storage Feature
- amplify storage add

### Add AWS Amplify Analytics Feature
- amplify analytics add

### Push the Data to AWS Amplify
- amplify push
