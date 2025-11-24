
🎥🎤 Camera + Voice Action Captcha (Prototype)

A browser-based captcha that verifies a human by combining camera actions and voice input.
To pass the captcha, the user must:

1. Allow camera + microphone access


2. Perform a specified action in front of the camera


3. Clearly say the phrase: “six seven”



Only after both the visual action and the audio phrase are detected, the captcha unlocks the “Proceed” button.

This prototype uses:

getUserMedia for camera/microphone access

Web Speech API for live speech transcription

Basic JS logic to validate the required phrase


No external servers, libraries, or ML models needed — fully client-side.
Perfect as a starting point for experimenting with gesture- or voice-based human verification.
