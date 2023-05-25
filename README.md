# Extracellular-electrophysiology-analysis
Paris-Saclay M1 Internship. Claustrum and Insular cortex were recorded simultaneously and extracellularly using the rodent brain slices with 32 channel multi electrode from NeuroNexus.
The spike sorting was done by BOSS program (https://github.com/BlackrockNeurotech/BOSS).
This is the code to subsequently analyse spikes and LFP from .ns6 raw data and .csv files outputed by BOSS app. The whole idea was to establish the directionality of the neuronal signals between the brain areas as well as analyse the single-cell signals inside individual brain regions.
The code, therefore, includes (cross) correlograms, (cross) spike-trigered averaged local field potential (STA-LFP), autocorrelations, crosscorrelations and inter spike intervals (ISI)
