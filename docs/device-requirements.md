# Device requirements

MUST, SHOULD and MAY are used as defined in [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119).

Each rule applies when the stock OS supports the hardware. Exceptions MAY be made for any rule. Raise them in the "Exceptions" field of your application.

## Calls and data
- Phones MUST support calls, mobile data and SMS.
- Phones MUST support emergency calls with a SIM inserted.
- Data-only devices are exempt from the calling rules.
- VoLTE and VoWiFi SHOULD work where the stock OS supports them.

## Audio
- Media playback MUST work.
- In-call audio and the loudspeaker MUST work.
- Every audio output the stock OS supports MUST work: speakers, headphone jack, USB-C and Bluetooth.
- Extra microphones and noise cancelling SHOULD work.

## Wi-Fi and Bluetooth
- Wi-Fi MUST work, and MUST report the same MAC address as the stock OS.
- The Wi-Fi hotspot MUST work.
- Bluetooth MUST work, including audio devices.

## USB
- File transfer (MTP) MUST work.
- USB tethering MUST work.

## Location
- GPS MUST work.

## Camera and video
- The front and main rear cameras MUST work for photos and video.
- Every rear and front camera SHOULD work.

## Fingerprint
- The fingerprint sensor MUST work, in-display sensors included.

## Sensors
- The accelerometer, gyroscope, proximity sensor and light sensor MUST work.
- Every other sensor the stock OS supports SHOULD work.

## Display
- Every refresh rate the panel supports SHOULD be selectable.
- Auto-brightness MUST work.

## NFC
- NFC MUST work.

## Security
- SELinux MUST be enforcing.

## Authorship and licences
- Every commit MUST keep its original author.
- The kernel source MUST be public.

## Stability
- The build MUST be stable enough for daily use. The team decides when it is ready.

These requirements are adapted from the LineageOS [device support requirements](https://github.com/LineageOS/charter/blob/master/device-support-requirements.md), licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
