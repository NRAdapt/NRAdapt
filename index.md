---
layout: default
---

# Synthesized Speech 
To demonstrate that our proposed model can significantly improve the similarity and quality of the synthesized speech, some samples are provided for comparison. In the brackets for every speaker's ID, **M** denotes the male speaker, and **F** denotes the female speaker. **Reference** denotes one of samples used for voice cloning in this environment, serving as the reference for the timbre similarity of the synthesized speech. **GT** denotes ground truth. **FastSpeech** denotes an open-source implementation of FastSpeech 2. **FastSpeech+SE** denotes the method based on the pre-trained speech enhancement model to improve the FastSpeech model for voice cloning. **NRAdapt** and **NRAdapt \*\*\*** denote the proposed method in our paper and its variants used for ablation studies respectively. In addition, a well-trained HIFI-GAN is used as the vocoder to generate waveform.

## Clean Environment

| Speaker ID | Target English Text | Reference | GT | FastSpeech | NRAdapt | NRAdapt CLN | NRAdapt clean | NRAdapt NI |
| :---: | :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 237(F) | "Here, Polly, hold your arms." he had only strength to gasp. | <audio controls><source src="./wavs/clean/Reference/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1089(M) | The falsehood of his position did not pain him. | <audio controls><source src="./wavs/clean/Reference/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1995(F) | Why should he pose as better than his fellows? | <audio controls><source src="./wavs/clean/Reference/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2300(M) | After that they were shown the meters by which the consumption of current was measured. | <audio controls><source src="./wavs/clean/Reference/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2830(M) | Just for that the world abhors the gospel. | <audio controls><source src="./wavs/clean/Reference/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2961(F) | Of the second or concurrent causes of sight i have already spoken, and i will now speak of the higher purpose of god in giving us eyes. | <audio controls><source src="./wavs/clean/Reference/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5105(M) | You must see, lieutenant, i should think, that we are not so near the coast of algeria as you imagined. | <audio controls><source src="./wavs/clean/Reference/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5683(F) | "I don't think, rachel dear, you heard me?" said dorcas. | <audio controls><source src="./wavs/clean/Reference/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/GT/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/FS/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_CLN/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_clean/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/clean/NRAdapt_noind/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |

## Multiple Noise Environment

| Speaker ID | Target English Text | Reference | GT | FastSpeech | FastSpeech+SE | NRAdapt | NRAdapt CLN | NRAdapt clean | NRAdapt NI |
| :---: | :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 237(F) | "Here, Polly, hold your arms." he had only strength to gasp. | <audio controls><source src="./wavs/multiple/Reference/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1089(M) | The falsehood of his position did not pain him. | <audio controls><source src="./wavs/multiple/Reference/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1995(F) | Why should he pose as better than his fellows? | <audio controls><source src="./wavs/multiple/Reference/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2300(M) | After that they were shown the meters by which the consumption of current was measured. | <audio controls><source src="./wavs/multiple/Reference/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2830(M) | Just for that the world abhors the gospel. | <audio controls><source src="./wavs/multiple/Reference/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2961(F) | Of the second or concurrent causes of sight i have already spoken, and i will now speak of the higher purpose of god in giving us eyes. | <audio controls><source src="./wavs/multiple/Reference/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5105(M) | You must see, lieutenant, i should think, that we are not so near the coast of algeria as you imagined. | <audio controls><source src="./wavs/multiple/Reference/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5683(F) | "I don't think, rachel dear, you heard me?" said dorcas. | <audio controls><source src="./wavs/multiple/Reference/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/GT/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/FS_SE/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_CLN/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_clean/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/multiple/NRAdapt_noind/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |

## Single Noise Environment

| Speaker ID | Target English Text | Reference | GT | FastSpeech | FastSpeech+SE | NRAdapt | NRAdapt CLN | NRAdapt clean | NRAdapt NI |
| :---: | :---- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 237(F) | "Here, Polly, hold your arms." he had only strength to gasp. | <audio controls><source src="./wavs/single/Reference/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/237_126133_000020_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1089(M) | The falsehood of his position did not pain him. | <audio controls><source src="./wavs/single/Reference/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/1089_134686_000012_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 1995(F) | Why should he pose as better than his fellows? | <audio controls><source src="./wavs/single/Reference/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/1995_1836_000004_000006.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2300(M) | After that they were shown the meters by which the consumption of current was measured. | <audio controls><source src="./wavs/single/Reference/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/2300_131720_000035_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2830(M) | Just for that the world abhors the gospel. | <audio controls><source src="./wavs/single/Reference/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/2830_3980_000014_000001.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 2961(F) | Of the second or concurrent causes of sight i have already spoken, and i will now speak of the higher purpose of god in giving us eyes. | <audio controls><source src="./wavs/single/Reference/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/2961_961_000026_000002.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5105(M) | You must see, lieutenant, i should think, that we are not so near the coast of algeria as you imagined. | <audio controls><source src="./wavs/single/Reference/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/5105_28241_000024_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 5683(F) | "I don't think, rachel dear, you heard me?" said dorcas. | <audio controls><source src="./wavs/single/Reference/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/GT/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/FS_SE/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_CLN/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_clean/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/single/NRAdapt_noind/5683_32879_000033_000000.wav" type="audio/wav">Your browser does not support the audio element.</audio> |