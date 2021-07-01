# farm_go

a project is experimente using flutter 

## Getting Started

To install dependencies, type `flutter pub get`

## Create new plugin or module repository

- To customize new repository, you should be at **packages** 's folder and use command to generate plugin `flutter create -t plugin hello_my_lib`
- If some **class_a.dart** need be encoded as json by **@JsonSerializable**, for example, will be generated like **class_a.g.dart** .Should follow steps:

1) Terminal app use `cd to_root_parent_folder` 
2) Import library module `git submodule add https://github.com/google/inject.dart`
3) Use command to generate `flutter pub run build_runner build` or `flutter packages pub run build_runner build`

Note: 
- If just want to generate json for specify folder of reposity and run `flutter pub run build_runner build` 
- Should delete previous generated **`*.g.dart`** file before run command above.

## Run on iOS/Android
- For example, open iOS Simulator runs first
- then run `fultter run`

## Run on web
- Kill all simulator/ emulator
- then run `fultter run`
