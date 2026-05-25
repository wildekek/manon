# Manon

Manon is a fully open source electric boat I designed and built.

This is some (rough) documentation so others can replicate this and build their own.

The motor is based on a old Epropulsion outboard, with a Flipsky 65161 motor. For this you need a [3D printable mount](https://cad.onshape.com/documents/3ef9fd0b7ee75e95a78ba9d7/w/2afbe9eba757c4d707f573a1/e/207345cef02e2442287dc739?renderMode=0&uiState=6a08afb2d2f123b75b04b34e)
To replace the tiller (throttle) electronics you need to use some [additional 3D printed parts](https://cad.onshape.com/documents/c148349990718a14b9edec6a/w/bba449e452757216954faad0/e/108e9faf802f9a33a70f8894?renderMode=0&uiState=6a08b55f6b694a8582c5a9e5)
For the Vesc Express I designed a [small waterproof case](https://cad.onshape.com/documents/5c700467c4155b5103ae18be/w/2405730056a696fa0bd4cc72/e/04e47c84cce0dbccdfbe640f?renderMode=0&uiState=6a08b8736b694a8582c5b49c).

Here is the wiring scheme for the electronics:
![Wiring scheme](./wiring%20scheme.png)

You can find the matching code for the various ESP32's in the [ESPHome](./ESPHome) folder.