# Claro

Highlight text. Read it in your language.

Claro is a small background translator for Mac and Windows, with a compact movable popup and a language picker. Spanish is the default.

## Download the beta

[Download Claro 0.1.0 beta 1](https://github.com/Cool-in/claro-downloads/releases/tag/v0.1.0-beta.1)

- **Windows x64:** installer included. The beta is unsigned; real Windows installation and selection behavior are awaiting tester verification.
- **Apple silicon Mac, macOS 26+:** Developer ID signed, Apple notarized and stapled app ZIP.

This is a beta for testing, not a completed commercial launch.

## Two translation modes

**Free with your API key.** Open Your provider and configure OpenAI or an OpenAI-compatible provider. Usage is billed by your provider.

**Offline translation.** Activate your Claro license in Offline, then download the optional 473 MiB model. It stays warm by default; disable Keep the model ready to unload it after one idle minute. A single lifetime license is intended for Mac and Windows. Paid checkout is not yet live while Polar account setup/review is incomplete.

Enable automatic translation in Translation settings. On macOS, grant Accessibility permission when requested. Apps that do not expose text selection can use Translate manually. Drag the popup or Settings from a noninteractive background area. Choose System, Light or Dark in the popup menu.

## Privacy and model notices

API mode sends selected text directly to your configured provider. Offline mode translates on your device after license activation and model download. Claro does not save translation history.

The offline model is Meta M2M100 418M converted to CTranslate2 int8. It is MIT licensed. [Model files, checksums, provenance and notices](https://github.com/Cool-in/claro-downloads/releases/tag/model-m2m100-int8-v1) accompany the model release. Claro sells its integrated offline feature; the underlying model remains open-source.

This public repository contains distribution assets and notices only. Application source is maintained separately in a private repository.
