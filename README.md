## speech-numpy
Sound files converted to numpy arrays

Original sound files were taken from the Google Speech Command dataset.
These files were first converted from WAV to mfcc (mel frequency ceptral coefficients). The WAV files are one second long sampled to 16KHz. 
The conversion is performed for each file in each class label which contains multiple files. Once all these were converted to mfcc vectors, these were appended to a large numpy array all listed in this repo.
