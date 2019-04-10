## Feature selection
-[Why, How and When to apply Feature Selection](https://towardsdatascience.com/why-how-and-when-to-apply-feature-selection-e9c69adfabf2)

Feature Selection is a very critical component in a Data Scientist’s workflow. When presented data with very high dimensionality, models usually choke because
1. Training time increases exponentially with number of features.
2. Models have increasing risk of overfitting with increasing number of features.

Three feature selection techniques:
1. Filter Methods
2. Wrapper Methods
3. Embedded Methods.


-[Introduction to Feature Selection methods with an example (or how to select the right variables?)](https://www.analyticsvidhya.com/blog/2016/12/introduction-to-feature-selection-methods-with-an-example-or-how-to-select-the-right-variables/)

- [Machine Learning with Signal Processing Techniques](http://ataspinar.com/2018/04/04/machine-learning-with-signal-processing-techniques/)


- Normalization:
  - Z-score
     - [Z-score normalization](https://t4tutorials.com/z-score-normalization-data-mining/)
     - [How raw data are normalized](http://howto.commetrics.com/methodology/statistics/normalization/)
  - What are the best normalization methods (Z-Score, Min-Max, etc.)? How would you choose a data normalization method? On [ResearchGate](https://www.researchgate.net/post/What_are_the_best_normalization_methods_Z-Score_Min-Max_etc_How_would_you_choose_a_data_normalization_method)
  - About Feature Scaling and Normalization – and the effect of standardization for machine learning algorithms, [by Sebastian Raschka](https://sebastianraschka.com/Articles/2014_about_feature_scaling.html)  
  - EMG normalization
    - Normalization of EMG Signals: To Normalize or Not to Normalize and What to Normalize to? [By Mark Halaki and Karen Ginn](https://www.intechopen.com/books/computational-intelligence-in-electromyography-analysis-a-perspective-on-current-applications-and-future-challenges/normalization-of-emg-signals-to-normalize-or-not-to-normalize-and-what-to-normalize-to-)
	  - the analysis of the frequency content of the EMG signal. In this type of analysis, the power spectrum of the EMG signal can be obtained by applying a Fast Fourier Transform to the EMG signal. The power density function of the EMG provides a distribution of the signal power as a function of frequency. Changes in the shape of the power density function of the EMG is usually analysed and shifts in the power density to lower frequencies is associated with fatigue. Since the shape of the power spectra is what is important, the amplitude of the EMG signal is not critical and EMG normalization is not required.
      - the decomposition of the EMG into wavelets for an analysis of motor unit firing patterns, or cross talk between muscles. In this analysis, the EMG signal is decomposed into small wavelets (small waveforms). The wavelets are then used to identify and characterize motor unit action potentials by compressing and/or rescaling the wavelets and identifying them in the EMG signal. Again, the amplitude of the EMG signal is not critical and EMG normalization is not required.
      - the time of the initiation of muscle activation. This type of analysis does not require EMG normalization as the time of activation is usually identified from the raw signal e.g. when the raw EMG signal amplitude reaches 2 [10] or 3 [11] standard deviations of the mean above baseline levels.
      - amplitude comparisons of signals from a given muscle between short term interventions/movements within an individual in the same session under the same experimental conditions without changes to the EMG electrode set-up [12] e.g. when comparing the EMG signal between different interventions/movements in a given muscle in each individual [13-16]. Because the absolute amplitude of the signal is meaningless, one cannot evaluate the level of activity in the muscle, but only that it is more or less active in one intervention/movement compared to the other. Therefore, comparison of muscle activity levels between muscles or individuals is not valid. 

