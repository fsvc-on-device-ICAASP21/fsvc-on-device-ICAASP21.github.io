# fsvc-on-device.github.io

## Efficient Strategies of Few-shot On-device Voice Cloning

**Authors**: Tasnima Sadekova, Vadim Popov, Dmitriy Polubotko, Vladimir Gogoryan, Ivan Vovk, Mikhail Kudinov

##### Abstract
Recent advances in neural text-to-speech allowed to build multi-speaker systems capable of performing high-fidelity speech generation. However, it is often desirable to be able to add a new voice to a text-to-speech system based on only a few recordings. Unfortunately, this is still a challenging problem for modern neural TTS solutions. In this work we study several approaches to design of on-device voice cloning. Starting from a multi-speaker TTS system we improve its quality for a target speaker either by fine-tuning feature generation module on a small speech sample or by using a GAN-based post-filter. We also compare performance of an autoregressive feature generation module based on Tacotron2 with a parallel solution based on Glow-TTS. We show that GAN-based post-filtering improves quality of a baseline zero-shot TTS system and demonstrate that a TTS system of a good quality can be obtained using only 1 minute of adaptation data with no more than 1.2k iterations of SGD proving feasibility of on-device voice cloning.