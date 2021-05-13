# ECG
An electrocardiogram (ECG) records the electrical activity of the heart’s conduction system which allows the cardiac chambers to contract. The results in an ECG are important because they can help physicians find out if a patient’s heart is beating abnormally. Using rhythm analysis on ECGs, physicians can diagnose AV junctional issues, atrial and ventricular cell problems, and SA node issues. 

Signal Acquisition:
To acquire a signal, one needs to use electrodes and appropriately place them on the body. Lead I should have a positive electrode on the left arm and the negative should be on the right arm. Lead II should have a positive electrode on the left leg and the negative electrode should be on the right arm. Lead III should have a positive electrode on the left leg and the negative electrode should be on the left arm. This data was collected on the cardio.mat file. 

Signal Processing: 
In order to process the signal, I initially plotted the raw signal on an appropriate time scale using the parameters of the fs needing to be 300 Hz. I then normalized the data by taking the absolute value of the signal, finding the maximum value of the absolute value signal, and plotting the ratio of the absolute value of the signal to the maximum against the time interval. The normalized signal gives a clearer idea of how the PQRST complexes compare to one another.

Analysis:
In the raw signal, the PQRST complex looks fairly typical to what one would expect. The P, Q, R, S, and T complexes seem to have an appropriate relation to each other. The raw signal makes it difficult to analyze differences between PQRST complexes which is why we normalize the data. The key difference between the raw and normalized signal data is the range from which the amplitude can be seen as the normalized data considers the amplitude as a ratio the maximum the raw data reached. When we look at the normalized signal data, it appears that the signal seems to be fairly constant meaning the heart is beating rhythmically. The normalized data can be interpreted by AI programs to help physicians diagnose patients if they have a cardiac issue. 
