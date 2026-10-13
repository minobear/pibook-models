# Pibook on-device model files

Download-only model files used by the Pibook app's photo editor. They run entirely on the
user's device; the app only downloads these files and never uploads photos or personal data.

| Release asset | Platform | SHA-256 |
|---|---|---|
| `lama_512_w8.tflite` (53,360,256 B) | Android (LiteRT) | `d53a131bd942ea5fe7d5b904f85fbe2eca446dc4f6ce0a34c75854abef6e237b` |
| `lama_512_w8.mlpackage.zip` (44,193,861 B) | iOS 16+ (Core ML) | `b0181a7be6f947d78c95ff489da53c363292c9640e61a1f4ddf653cd95f3f0e1` |

Licence: LaMa (big-lama) is Apache-2.0 — see `LICENSE-LaMa-Apache-2.0.txt` and `NOTICE.txt`
for the upstream copyright and the list of modifications.

Assets are immutable: a new model version is published as a new release with a new file name.
