# Reducing Speaker Residual by Considering Pinhole Effect in Voice Anonymization

*Anonymous submission to Interspeech 2026*

## Abstract

De-identification is a critical objective of voice anonymization, requiring the absence of residual original speaker information in the anonymized speech. In state-of-the-art disentanglement-based frameworks, this is achieved by disentangling original speaker attributes from non-speaker attributes, which are represented separately, and substituting the speaker representation with that of a pseudo-speaker. Leakage of speaker attributes in non-speaker representations results in residual original speaker information in the anonymized speech. To this end, this paper proposes a fine-tuning strategy on the content and prosody extractors by incorporating a pinhole-based loss function applied to the anonymized speech. The linkability of the anonymized speech utterances is reduced, thereby minimizing the residual original speaker information in the anonymized speech. The effectiveness of the proposed pinhole-based fine-tuning strategy for voice privacy protection is validated through experiments conducted across multiple anonymization frameworks.

**Index Terms:** voice anonymization, residual speaker attributes, linkability, pinhole-based loss

---

## Audio Samples

The audio samples are organized by anonymization system and method.  
The suffix `-w` denotes the corresponding method fine-tuned with the proposed pinhole-based loss.

---

## xvector-based

| File name | RS | RS-w | A2O | A2O-w | GAN | GAN-w | IDMap | IDMap-w |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | <audio controls src="xvector/RS/1462-170142-0000.wav"></audio> | <audio controls src="xvector/RS-w/1462-170142-0000.wav"></audio> | <audio controls src="xvector/a2o/1462-170142-0000.wav"></audio> | <audio controls src="xvector/a2o-w/1462-170142-0000.wav"></audio> | <audio controls src="xvector/GAN/1462-170142-0000.wav"></audio> | <audio controls src="xvector/GAN-w/1462-170142-0000.wav"></audio> | <audio controls src="xvector/idmap/1462-170142-0000.wav"></audio> | <audio controls src="xvector/idmap-w/1462-170142-0000.wav"></audio> |
| `1462-170142-0001.wav` | <audio controls src="xvector/RS/1462-170142-0001.wav"></audio> | <audio controls src="xvector/RS-w/1462-170142-0001.wav"></audio> | <audio controls src="xvector/a2o/1462-170142-0001.wav"></audio> | <audio controls src="xvector/a2o-w/1462-170142-0001.wav"></audio> | <audio controls src="xvector/GAN/1462-170142-0001.wav"></audio> | <audio controls src="xvector/GAN-w/1462-170142-0001.wav"></audio> | <audio controls src="xvector/idmap/1462-170142-0001.wav"></audio> | <audio controls src="xvector/idmap-w/1462-170142-0001.wav"></audio> |
| `84-121550-0000.wav` | <audio controls src="xvector/RS/84-121550-0000.wav"></audio> | <audio controls src="xvector/RS-w/84-121550-0000.wav"></audio> | <audio controls src="xvector/a2o/84-121550-0000.wav"></audio> | <audio controls src="xvector/a2o-w/84-121550-0000.wav"></audio> | <audio controls src="xvector/GAN/84-121550-0000.wav"></audio> | <audio controls src="xvector/GAN-w/84-121550-0000.wav"></audio> | <audio controls src="xvector/idmap/84-121550-0000.wav"></audio> | <audio controls src="xvector/idmap-w/84-121550-0000.wav"></audio> |
| `84-121550-0001.wav` | <audio controls src="xvector/RS/84-121550-0001.wav"></audio> | <audio controls src="xvector/RS-w/84-121550-0001.wav"></audio> | <audio controls src="xvector/a2o/84-121550-0001.wav"></audio> | <audio controls src="xvector/a2o-w/84-121550-0001.wav"></audio> | <audio controls src="xvector/GAN/84-121550-0001.wav"></audio> | <audio controls src="xvector/GAN-w/84-121550-0001.wav"></audio> | <audio controls src="xvector/idmap/84-121550-0001.wav"></audio> | <audio controls src="xvector/idmap-w/84-121550-0001.wav"></audio> |

---

## ASRBN

| File name | RS | RS-w | A2O | A2O-w | GAN | GAN-w | IDMap | IDMap-w |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | <audio controls src="asrbn/RS/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/RS-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/a2o/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/a2o-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/GAN/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/GAN-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/idmap/1462-170142-0000.wav"></audio> | <audio controls src="asrbn/idmap-w/1462-170142-0000.wav"></audio> |
| `1462-170142-0001.wav` | <audio controls src="asrbn/RS/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/RS-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/a2o/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/a2o-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/GAN/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/GAN-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/idmap/1462-170142-0001.wav"></audio> | <audio controls src="asrbn/idmap-w/1462-170142-0001.wav"></audio> |
| `84-121550-0000.wav` | <audio controls src="asrbn/RS/84-121550-0000.wav"></audio> | <audio controls src="asrbn/RS-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn/a2o/84-121550-0000.wav"></audio> | <audio controls src="asrbn/a2o-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn/GAN/84-121550-0000.wav"></audio> | <audio controls src="asrbn/GAN-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn/idmap/84-121550-0000.wav"></audio> | <audio controls src="asrbn/idmap-w/84-121550-0000.wav"></audio> |
| `84-121550-0001.wav` | <audio controls src="asrbn/RS/84-121550-0001.wav"></audio> | <audio controls src="asrbn/RS-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn/a2o/84-121550-0001.wav"></audio> | <audio controls src="asrbn/a2o-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn/GAN/84-121550-0001.wav"></audio> | <audio controls src="asrbn/GAN-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn/idmap/84-121550-0001.wav"></audio> | <audio controls src="asrbn/idmap-w/84-121550-0001.wav"></audio> |

---

## ASRBN-GST

| File name | RS | RS-w | A2O | A2O-w | GAN | GAN-w | IDMap | IDMap-w |
|---|---|---|---|---|---|---|---|---|
| `1462-170142-0000.wav` | <audio controls src="asrbn-gst/RS/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/RS-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/a2o/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/a2o-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/GAN/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/GAN-w/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/idmap/1462-170142-0000.wav"></audio> | <audio controls src="asrbn-gst/idmap-w/1462-170142-0000.wav"></audio> |
| `1462-170142-0001.wav` | <audio controls src="asrbn-gst/RS/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/RS-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/a2o/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/a2o-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/GAN/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/GAN-w/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/idmap/1462-170142-0001.wav"></audio> | <audio controls src="asrbn-gst/idmap-w/1462-170142-0001.wav"></audio> |
| `84-121550-0000.wav` | <audio controls src="asrbn-gst/RS/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/RS-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/a2o/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/a2o-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/GAN/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/GAN-w/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/idmap/84-121550-0000.wav"></audio> | <audio controls src="asrbn-gst/idmap-w/84-121550-0000.wav"></audio> |
| `84-121550-0001.wav` | <audio controls src="asrbn-gst/RS/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/RS-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/a2o/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/a2o-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/GAN/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/GAN-w/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/idmap/84-121550-0001.wav"></audio> | <audio controls src="asrbn-gst/idmap-w/84-121550-0001.wav"></audio> |
