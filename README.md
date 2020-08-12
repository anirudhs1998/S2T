# S2T
Speech to Text conversion using Kaldi

If the audio file is sampled at 16 khz, then use the following to convert it to 8 khz

		sox <input-file.wav> -r 8000 <output-file.wav> rate

Put the audio files in the directory - ~/Desktop/ASR_demo/audio/

Run the following script from the directory  ~/kaldi/kaldi/egs/aspire/s5/
		
		chmod u+x ./FINAL.sh
		
		./FINAL.sh <audiofile1> <audiofile2> <audiofile3> ......

Do not write the file extension. Example: Mention "audio1.wav" as "audio1" in the command line.
      
