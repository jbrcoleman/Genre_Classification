# Genre_Classification
. The dataset we used comprised of 1000 30 second clips of songs within 10 different 
genres: 1. Metal 2. Rock 3. Blues 4. Classical 5. Hip Hop 6. Country 7. Pop 8. Disco 9. Jazz 10. 
Reggae. We took a couple different approaches in building a model to classify these song 
structures. We used CNNs to analyze the Mel-Spectrogram of the song to identify the different 
genres. We also used the CSVs provided by Kaggle to build a dense neural network that
contained 57 data points of each clip like temp, pitch, and Mel-frequency cepstrum (MFCC) 
data. The best network used the data provided by Kaggle that included all of the data points for 
the songs spit into 3 second clips and was able to achieve an accuracy of 90.77% on the test 
data set. The best CNN model was able to achieve an accuracy of 67.59% on the MFCC images 
created from the 30 second clips.
