# learning_dart

Learning dart in flutter

## To start with flutter

### create flutter app using :

`flutter create my_app`
more or less commands
`flutter create learning_dart`
`flutter create --org com.yourdomain your_app_name`
`flutter create --org com.yourdomain -t skeleton your_app_name`
`flutter create --androidx -t app --org com.companyname.packagename -a kotlin -i swift myapp`

### Explore Yourself by Flutter CLI for more help

`flutter create --help` OR `flutter help`

## Requirments dependency

as we are going to use firebase as gateway we need to install few firebase :
`flutter pub add firebase_core firebase_auth cloud_firestore firebase_analytics`

if you want to delete a dependency
`flutter pub remove flutter`

to delete or clean error dependency
`flutter clean` OR `flutter clean 'platform'`

for already added dependency in existing project, to download the dependency files use :
`flutter pub get`
