# S2I Translation Datasets

Audiovisual data for Sound-to-Image (S2I) experiments.

This repository consists of audiovisual data for training and testing the models available in https://github.com/leofanzeres/s2i.git

![1-s Mel spectrogram segments and respective central frames extracted from a video track of the class Rail transport.](images/spectrogram_segments_and_video_frames.png)
1-s Mel spectrogram segments and respective central frames extracted from a video track of the class Rail transport

The datasets consist of log-Mel spectrograms computed from 1-s audio segments and the respective frames from the original video tracks. The complete dataset VEGAS was made available by Zhou et al. during their study on crossmodal generation (![Visual to Sound: Generating Natural Sound for Videos in the Wild, CVPR, 2018][2018]][zhou-2018]). It consists of 28,109 videos of 10-s maximal duration distributed in 10 sound classes, among which we use five: Baby crying, Dog, Rail transport, Fireworks, and Water flowing.

This dataset is made available under a [Creative Commons Attribution 4.0 International License][cc-by] [![CC BY 4.0][cc-by-image]][cc-by]

[zhou-2018]: http://creativecommons.org/licenses/by/4.0/
[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/80x15.png
