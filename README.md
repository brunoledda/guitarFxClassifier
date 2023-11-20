# Guitar Fx Classifier

Applicazione Android in grado di classificare diversi effetti per chitarra, tramite l’utilizzo del microfono di uno smartphone e di un modello classificatore (CNN) appositamente addestrato.

- All'interno della cartella audio sono presenti i file audio in formato .wav usati per il training e scaricati al seguente link: https://doi.org/10.5281/zenodo.7544032  (Stein, M. (2023). IDMT-SMT-Audio-Effects Dataset (1.0.0) [Data set]. Zenodo.)
- il file annotations1.csv contiene le informazioni associate a ciascun file audio, compresa la label di appartenenza (0: no effects, 1: Eq, 2: Feedback delay, 3: Slapback delay, 4: Reverb, 5: Chorus, 6: Flanger, 7: Phaser, 8: Tremolo, 9: Vibrato, 10: Distortion, 11: Overdrive)
- il file gfxclassifier_training.ipynb è un notebook contenente l'intero codice relativo al training del modello. Si consiglia l'utilizzo di Kaggle per ridurre i tempi di addestramento.
- la cartella GuitarFxClassifier fa riferimento al progetto da aprire su Android Studio contenente il codice sorgente dell'applicazione.
