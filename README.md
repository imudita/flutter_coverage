# Flutter Console Coverage Test

This small dart tools is used to generate Flutter Coverage Test to console

## How to run (Windows 10 Environment)

## From Android Studio Terminal
### run the following command to make sure all flutter library is up-to-date
```
E:\test\coverage> flutter pub get
Running "flutter pub get" in coverage...                            0.5s
```
### run the following command to generate lcov.info on coverage directory
```
E:\test\coverage>flutter test --coverage
00:02 +1: All tests passed!
```
### run the tool to generate report form lcov.info
```
E:\test\coverage> dart lib\coverage.dart coverage\lcov.info
lib/coverage.dart: Warning: Interpreting this as package URI, 'package:coverage/coverage.dart'.
---------------------------------------------|---------|---------|---------|-------------------|
File                                         |% Branch | % Funcs | % Lines | Uncovered Line #s |
---------------------------------------------|---------|---------|---------|-------------------|
lib\                                         |         |         |         |                   |
 main.dart                                   |  100.00 |  100.00 |   92.59 |                3,4|
---------------------------------------------|---------|---------|---------|-------------------|

E:\test\coverage>
```
## How to run (Linux/Mac Environment)

## From Android Studio Terminal
### run the following command to make sure all flutter library is up-to-date
```
% flutter pub get
Running "flutter pub get" in coverage...                            0.5s
```
### run the following command to generate lcov.info on coverage directory
```
% flutter test --coverage
00:02 +1: All tests passed!
```
### run the tool to generate report form lcov.info
```
% dart lib/coverage.dart coverage/lcov.info
lib/coverage.dart: Warning: Interpreting this as package URI, 'package:coverage/coverage.dart'.
---------------------------------------------|---------|---------|---------|-------------------|
File                                         |% Branch | % Funcs | % Lines | Uncovered Line #s |
---------------------------------------------|---------|---------|---------|-------------------|
lib/                                         |         |         |         |                   |
 main.dart                                   |  100.00 |  100.00 |   92.59 |                3,4|
---------------------------------------------|---------|---------|---------|-------------------|

%
```