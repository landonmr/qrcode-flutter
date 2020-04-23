# qrcode

POC project to act as a base project setup

# Functionality

1.  Fetches a generated random seed to create the QR code
2.  Seed has an expiration date.
3.  Display QR code
4.  Scaning a QR code and check the expiration


The project follows the MVVM (model view view-model) design paradigm.  It was constructed using `VS Code 1.43.0` running `Flutter 1.12.13+hotfix.5 • channel stable`

**Note: missing dependency injection to remove passing dependencies via constructors, and the Provider/Change notifier state management pattern.** 
# Unit test

Run the following in the root of the directory to run the unit tests.

`flutter test test/qr_code_vm_test.dart`