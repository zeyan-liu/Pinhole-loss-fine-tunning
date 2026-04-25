# Reducing Speaker Residual by Considering Pinhole Effect in Voice Anonymization

*Anonymous submission to Interspeech 2026*

## Abstract

De-identification is a critical objective of voice anonymization, requiring the absence of residual original speaker information in the anonymized speech. In state-of-the-art disentanglement-based frameworks, this is achieved by disentangling original speaker attributes from non-speaker attributes, which are represented separately, and substituting the speaker representation with that of a pseudo-speaker. Leakage of speaker attributes in non-speaker representations results in residual original speaker information in the anonymized speech. To this end, this paper proposes a fine-tuning strategy on the content and prosody extractors by incorporating a pinhole-based loss function applied to the anonymized speech. The linkability of the anonymized speech utterances is reduced, thereby minimizing the residual original speaker information in the anonymized speech. The effectiveness of the proposed pinhole-based fine-tuning strategy for voice privacy protection is validated through experiments conducted across multiple anonymization frameworks.

**Index Terms:** voice anonymization, residual speaker attributes, linkability, pinhole-based loss

---

## Audio Samples

The audio samples are organized by anonymization system, anonymization method, and whether pinhole-based fine-tuning is applied.

- `w/o` denotes the original method without pinhole-based fine-tuning.
- `w/` denotes the corresponding method with pinhole-based fine-tuning.
- Click `audio` to open and play the corresponding wav file.

---

## Demo Page
# You can access the audio samples at  [https://zeyan-liu.github.io/Pinhole-loss-fine-tunning/].

## xvector-based

| File name | a2o w/o | a2o w/ | RS w/o | RS w/ | GAN w/o | GAN w/ | IDMap-Diff w/o | IDMap-Diff w/ |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | [audio](xvector/a2o/1462-170142-0000.wav) | [audio](xvector/a2o-w/1462-170142-0000.wav) | [audio](xvector/RS/1462-170142-0000.wav) | [audio](xvector/RS-w/1462-170142-0000.wav) | [audio](xvector/GAN/1462-170142-0000.wav) | [audio](xvector/GAN-w/1462-170142-0000.wav) | [audio](xvector/idmap/1462-170142-0000.wav) | [audio](xvector/idmap-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](xvector/a2o/1462-170142-0001.wav) | [audio](xvector/a2o-w/1462-170142-0001.wav) | [audio](xvector/RS/1462-170142-0001.wav) | [audio](xvector/RS-w/1462-170142-0001.wav) | [audio](xvector/GAN/1462-170142-0001.wav) | [audio](xvector/GAN-w/1462-170142-0001.wav) | [audio](xvector/idmap/1462-170142-0001.wav) | [audio](xvector/idmap-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](xvector/a2o/84-121550-0000.wav) | [audio](xvector/a2o-w/84-121550-0000.wav) | [audio](xvector/RS/84-121550-0000.wav) | [audio](xvector/RS-w/84-121550-0000.wav) | [audio](xvector/GAN/84-121550-0000.wav) | [audio](xvector/GAN-w/84-121550-0000.wav) | [audio](xvector/idmap/84-121550-0000.wav) | [audio](xvector/idmap-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](xvector/a2o/84-121550-0001.wav) | [audio](xvector/a2o-w/84-121550-0001.wav) | [audio](xvector/RS/84-121550-0001.wav) | [audio](xvector/RS-w/84-121550-0001.wav) | [audio](xvector/GAN/84-121550-0001.wav) | [audio](xvector/GAN-w/84-121550-0001.wav) | [audio](xvector/idmap/84-121550-0001.wav) | [audio](xvector/idmap-w/84-121550-0001.wav) |

---

## ASRBN

| File name | a2o w/o | a2o w/ | RS w/o | RS w/ | GAN w/o | GAN w/ | IDMap-Diff w/o | IDMap-Diff w/ |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | [audio](asrbn/a2o/1462-170142-0000.wav) | [audio](asrbn/a2o-w/1462-170142-0000.wav) | [audio](asrbn/RS/1462-170142-0000.wav) | [audio](asrbn/RS-w/1462-170142-0000.wav) | [audio](asrbn/GAN/1462-170142-0000.wav) | [audio](asrbn/GAN-w/1462-170142-0000.wav) | [audio](asrbn/idmap/1462-170142-0000.wav) | [audio](asrbn/idmap-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](asrbn/a2o/1462-170142-0001.wav) | [audio](asrbn/a2o-w/1462-170142-0001.wav) | [audio](asrbn/RS/1462-170142-0001.wav) | [audio](asrbn/RS-w/1462-170142-0001.wav) | [audio](asrbn/GAN/1462-170142-0001.wav) | [audio](asrbn/GAN-w/1462-170142-0001.wav) | [audio](asrbn/idmap/1462-170142-0001.wav) | [audio](asrbn/idmap-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](asrbn/a2o/84-121550-0000.wav) | [audio](asrbn/a2o-w/84-121550-0000.wav) | [audio](asrbn/RS/84-121550-0000.wav) | [audio](asrbn/RS-w/84-121550-0000.wav) | [audio](asrbn/GAN/84-121550-0000.wav) | [audio](asrbn/GAN-w/84-121550-0000.wav) | [audio](asrbn/idmap/84-121550-0000.wav) | [audio](asrbn/idmap-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](asrbn/a2o/84-121550-0001.wav) | [audio](asrbn/a2o-w/84-121550-0001.wav) | [audio](asrbn/RS/84-121550-0001.wav) | [audio](asrbn/RS-w/84-121550-0001.wav) | [audio](asrbn/GAN/84-121550-0001.wav) | [audio](asrbn/GAN-w/84-121550-0001.wav) | [audio](asrbn/idmap/84-121550-0001.wav) | [audio](asrbn/idmap-w/84-121550-0001.wav) |

---

## ASRBN-GST

| File name | a2o w/o | a2o w/ | RS w/o | RS w/ | GAN w/o | GAN w/ | IDMap-Diff w/o | IDMap-Diff w/ |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | [audio](asrbn-gst/a2o/1462-170142-0000.wav) | [audio](asrbn-gst/a2o-w/1462-170142-0000.wav) | [audio](asrbn-gst/RS/1462-170142-0000.wav) | [audio](asrbn-gst/RS-w/1462-170142-0000.wav) | [audio](asrbn-gst/GAN/1462-170142-0000.wav) | [audio](asrbn-gst/GAN-w/1462-170142-0000.wav) | [audio](asrbn-gst/idmap/1462-170142-0000.wav) | [audio](asrbn-gst/idmap-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](asrbn-gst/a2o/1462-170142-0001.wav) | [audio](asrbn-gst/a2o-w/1462-170142-0001.wav) | [audio](asrbn-gst/RS/1462-170142-0001.wav) | [audio](asrbn-gst/RS-w/1462-170142-0001.wav) | [audio](asrbn-gst/GAN/1462-170142-0001.wav) | [audio](asrbn-gst/GAN-w/1462-170142-0001.wav) | [audio](asrbn-gst/idmap/1462-170142-0001.wav) | [audio](asrbn-gst/idmap-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](asrbn-gst/a2o/84-121550-0000.wav) | [audio](asrbn-gst/a2o-w/84-121550-0000.wav) | [audio](asrbn-gst/RS/84-121550-0000.wav) | [audio](asrbn-gst/RS-w/84-121550-0000.wav) | [audio](asrbn-gst/GAN/84-121550-0000.wav) | [audio](asrbn-gst/GAN-w/84-121550-0000.wav) | [audio](asrbn-gst/idmap/84-121550-0000.wav) | [audio](asrbn-gst/idmap-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](asrbn-gst/a2o/84-121550-0001.wav) | [audio](asrbn-gst/a2o-w/84-121550-0001.wav) | [audio](asrbn-gst/RS/84-121550-0001.wav) | [audio](asrbn-gst/RS-w/84-121550-0001.wav) | [audio](asrbn-gst/GAN/84-121550-0001.wav) | [audio](asrbn-gst/GAN-w/84-121550-0001.wav) | [audio](asrbn-gst/idmap/84-121550-0001.wav) | [audio](asrbn-gst/idmap-w/84-121550-0001.wav) |
