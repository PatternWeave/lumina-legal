# LightWeave Privacy Policy

Last updated: 23 August 2026

LightWeave (“the app”) is a lighting companion for Philips Hue. You can speak or type lighting commands and change lights in your home.

## What LightWeave collects

LightWeave does not create an account. It does not run ads or analytics SDKs.

On this device the app stores:

- Apple purchase account token (UserDefaults)
- Hue Bridge address and application key (Keychain / UserDefaults)
- Hue OAuth access and refresh tokens if you enable anywhere access (Keychain)
- Optional Microsoft Phi-3 Mini model weights after you agree to download them

You do not need an xAI account. Named lighting commands are matched on this iPhone and sent to your Hue Bridge or Hue Remote API.

## Audio and on-device processing

Microphone audio is turned into text with Apple Speech Recognition, preferring on-device recognition. Silero VAD and a local noise suppressor run on the same phone so background noise is less likely to be treated as a command.

Clear commands (room and light names, on/off, brightness) are parsed on device. If you agree to download Phi-3 Mini, vague phrasing can be interpreted by that model on the iPhone. Weights come from Hugging Face (`mlx-community/Phi-3-mini-4k-instruct-4bit`) once, then stay on device.

Tapping rooms and scenes does not run speech recognition or Phi-3. You can turn on-device voice off in Settings. Purchase receipts are processed by Apple.

## Lighting control

Commands go to your Philips Hue Bridge on the local network, or to the Hue Remote API (`api.meethue.com`) when you sign in with Hue. Signify’s processing is described in the [Philips Hue privacy policy](https://www.philips-hue.com/legal/privacy-policy).

## Permissions

- **Microphone** — speak lighting commands.
- **Speech Recognition** — turn speech into text on this iPhone.
- **Local network** — find the Hue Bridge on Wi‑Fi.

You can deny either permission. Without the microphone you can still type. Without local network you can still use Hue Remote sign-in.

## Third parties

- Microsoft / Hugging Face — optional one-time Phi-3 Mini weight download
- Apple Speech Recognition
- Signify / Philips Hue (Bridge and Remote API)

LightWeave does not sell personal data and does not send lighting commands to xAI.

## Safety

You can report a reply, pause on-device voice, or turn it off in Settings. Email support from the app. LightWeave is a lighting controller, not a social network.

## Subscriptions

Voice Unlimited (`com.anthonytaves.lightweave.voice.monthly`) is an auto-renewable subscription billed through Apple for Home Tips and lighting schedules. It renews each month unless you cancel at least 24 hours before the period ends. Manage or cancel in iOS Settings → Apple ID → Subscriptions. Pro (`com.anthonytaves.lightweave.pro`) is a one-time purchase. Restore purchases is in LightWeave Settings. Named voice control is included at no extra charge.

## Contact

Email [aataves@icloud.com](mailto:aataves@icloud.com). Public policy and support: [github.com/PatternWeave/lightweave-legal](https://github.com/PatternWeave/lightweave-legal).
