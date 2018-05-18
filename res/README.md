
- Happens on both Android and iOS.

- On Android 1.13 doesn't work, 1.14 does.  On iOS both don't work.

- Adding this (which comes from Ratchet) appears to fix iOS in ALL cases, but not on Android

            body {
                position: fixed;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0;
            }

- On Digby you have to slide up before it will slide left (maybe Fastclick does something)


chrome://inspect
