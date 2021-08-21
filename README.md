# S2I Translation Datasets

Audiovisual data for Sound-to-Image (S2I) experiments.

![1-s Mel spectrogram segments and respective central frames extracted from a video track of the class Rail transport.][image-01]
1-s Mel spectrogram segments and respective central frames extracted from a video track of the class Rail transport

This repository provides the audiovisual data required for training and testing the models available in https://github.com/leofanzeres/s2i.git. The datasets consist of log-Mel spectrograms computed from 1-s audio segments and the respective frames from the original video tracks. The complete VEGAS dataset was made available by Zhou et al. during their study on crossmodal generation (![Visual to Sound: Generating Natural Sound for Videos in the Wild, CVPR, 2018][zhou-2018]). It consists of 28,109 videos of 10-s maximal duration distributed in 10 sound classes, among which we use five: Baby crying, Dog, Rail transport, Fireworks, and Water flowing.

This dataset is made available under a [Creative Commons Attribution 4.0 International License][cc-by] [![CC BY 4.0][cc-by-image]][cc-by]

[image-01]: images/spectrogram_segments_and_video_frames.png
[zhou-2018]: https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Visual_to_Sound_CVPR_2018_paper.pdf
[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/80x15.png
