# corpusdemo
This is a sample of our corpus to support our paper submitted at INTERSPEECH 2019. Due to sponsor restrictionk, we cannot disclose our full corpus.

Inside the "audio_data" folder, all audio files are organized speaker-wise: i.e., all audio files of the same speaker are inside the same folder.

Inside "data/train" folder, meta data are given to according to Kaldi [1] format. "text" contains the transcription of each of the audio files. "spk2gender" contains gender information for each speaker. "utt2spk" maps each utterance (each audio file) to the corresponding speaker. "wav.scp" contains the path for each of the audio files.

##Reference:

[1] D. Povey, A. Ghoshal, G. Boulianne, L. Burget, O. Glembek, N. Goel, M. Hannemann, P. Motlicek, Y. Qian, P. Schwarz et al.,
"The kaldi speech recognition toolkit," IEEE Signal Processing Society, Tech. Rep., 2011
