# Changelog

## v2.0.1

- Reference signalapp/webrtc@4044c
  - Fixes a call forking bug
  - Improves connectivity using PORTALLOCATOR_ENABLE_ANY_ADDRESS_PORTS
  - Cherry picked updates from WebRTC

- Disable TURN port pruning

- Fix glare handling before connection

## v2.0.0

- Add Multi-Ring feature

- Android: Fix video encoder crash on some devices

- Update build documentation

- Update Rust dependencies

## v1.3.1

- Fix issue preventing some calls from ringing

## v1.3.0

- Update build documentation

- Reference signalapp/webrtc@4044

## v1.2.0

- Move to vendored WebRTC at signalapp/webrtc

- Reference signalapp/webrtc@3987, includes cherry picked updates from WebRTC 4044

## v1.1.0

- Disable unused audio codecs and RTP header extensions

- Adjust settings and logging

- iOS: Minor optimizations

## v1.0.2

- Cherry pick updates from WebRTC 4044

## v1.0.1

- Android: improve logging

## v1.0.0

- Add Call Manager component

## v0.3.3

- Update WebRTC to 3987

- Update Rust dependencies

- iOS: build system improvements

## v0.3.2

- iOS: Fix iOS 13 issue with camera capture

## v0.3.1

- Android: Filter list of cameras when switching cameras

## v0.3.0

- Update WebRTC to m79

- Android: Improve WebRTC debug logging

## v0.2.0

- Improve logging on Android

- Build system improvements

## v0.1.9

- Make termination a two-phase close and dispose operation

## v0.1.8

- Improve logging on Android

- Patch WebRTC M78 for AudioRecord regression

## v0.1.7

- Add integration tests

- Build system fixes and clean up

## v0.1.6

- Android: Use an application supplied logging object

## v0.1.5

- Update WebRTC to m78

- Add integration tests

- Build system fixes and clean up

## v0.1.4

- Update Makefile targets for 'clean' and 'distclean'

- Simplify the IceReconnecting logic

- Remove non-critical DataChannel error callbacks

## v0.1.3

- Add IceReconnectingState

## v0.1.2

- iOS Support

- Update WebRTC to m77

## v0.1.1

- Initial Release

- Based on WebRTC release m76
