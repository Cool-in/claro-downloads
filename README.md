# Claro

Highlight text. Read it in your language.

Claro is a small background translator for Mac and Windows, with a compact movable popup and a language picker. Spanish is the default.

## Download

**Mac:** [Download Claro 0.2.0](https://github.com/Cool-in/claro-downloads/releases/tag/v0.2.0). Apple silicon, macOS 26 or later. Developer ID signed and notarized by Apple. Unzip and move Claro to Applications.

**Windows x64:** [Claro 0.1.0 beta 1](https://github.com/Cool-in/claro-downloads/releases/tag/v0.1.0-beta.1). This installer is an unsigned beta and is still awaiting tester verification.

## Free, and a one-time €10 option

**Free with your API key.** Claro is free and open source under the MIT licence. Open Your provider and configure OpenAI or an OpenAI-compatible provider. Usage is billed by your provider, not by Claro.

**Claro Offline, €10 once.** A single lifetime licence for private, on-device translation on Mac and Windows. No subscription, no API key and no per-use cost.

- **What you get:** a licence key that unlocks the one-click download of the optional 473 MiB offline model inside Claro.
- **How it is delivered:** digitally. The licence key is issued by Polar straight after purchase and sent to your purchase email. Paste it into Offline in Claro and press Activate.
- **How to buy:** [Get Claro Offline for €10](https://buy.polar.sh/polar_cl_l1g5nvqcLrMGlyjIzfLVnCDr8gVXx3fdZdQH234ytlo). Payments are handled by Polar as merchant of record. Checkout opens to the public once Polar's account review is complete.
- **Good to know:** the model stays warm by default; turn off Keep the model ready to unload it after one idle minute. Offline quality can differ from cloud models.

## Support

Questions, problems or licence trouble: [open an issue](https://github.com/Cool-in/claro/issues) on the Claro repository.

Enable automatic translation in Translation settings. On macOS, grant Accessibility permission when requested. Apps that do not expose text selection can use Translate manually. Drag the popup or Settings from a noninteractive background area. Choose System, Light or Dark in the popup menu.

## Privacy and model notices

API mode sends selected text directly to your configured provider. Offline mode translates on your device after license activation and model download. Claro does not save translation history.

The offline model is Meta M2M100 418M converted to CTranslate2 int8. It is MIT licensed. [Model files, checksums, provenance and notices](https://github.com/Cool-in/claro-downloads/releases/tag/model-m2m100-int8-v1) accompany the model release. Claro sells its integrated offline feature; the underlying model remains open-source.

This repository contains distribution assets and notices only. The application source is public at [Cool-in/claro](https://github.com/Cool-in/claro).
