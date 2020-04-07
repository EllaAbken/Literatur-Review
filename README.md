# Literatur-Review
Search strategy
Functional near infrared spectroscopy (fNIR) is an imaging technique that measures the oxygen supply to the brain in response to cognitive tasks. The aim is to map the location and structure of active brain areas.  This should help to improve the diagnosis of neurodegenerative diseases (such as ADHD, speech disorders or autism).  

A channel that does not provide data from active brain regions causes the signal-to-noise ratio to deteriorate. Removal of signal components not related to brain activity improves SNR, measurement time and reduces the repetition rate. To extract a bad channel, it must first be defined by criteria to separate it from the other channels. A "bad channel" was determined using the following criteria (doi:10.3791/58807): 

 
1. Exclude channels in which there is no signal change for several continuous samples, which is indicated by a flat line when plotting the time series. 

 2. Calculate the coefficient of variation CV = SD/mean*100 for the raw attenuation data. Exclude channels in which the CV is above a predefined percentage (e.g., 10%; see for instance van der Kant et al.21).  

3. Plot the power spectrum of the signal. If there is no heartbeat visible in the signal spectrum around 1 Hz, as indicated by an increased power in this frequency band, exclude the channel from the analysis.  

4. Visually inspect all data before and/or after preprocessing. Decide whether to include the channel based on the objective criteria, described in 3.2.1 – 3.2.3, as well as on subjective visual detection of noisy channels. 

In order to identify and extract a bad channel, as well as to find further criteria, a literature search in the field of near-infrared spectroscopy was carried out. For this purpose, the database of PubMed and Scropus were used to obtain reviews with the following keywords: '("fNIRS"[Title/Abstract] OR ' + \ '"functional near-infrared spectroscopy"[Title/Abstract] OR ' + \ '"NIRS"[Title/Abstract] OR ' + \ '"near-infrared spectroscopy"[Title/Abstract]) AND ' + \ '"humans"[MeSH Terms] AND ("' + YEAR + '/01/01"[PDAT] : "' + YEAR + '/12/31"[PDAT])' for PubMed and '(TITLE-ABS-KEY("fNIRS") OR ' + \ 'TITLE-ABS-KEY("functional near-infrared spectroscopy") OR ' + \ 'TITLE-ABS-KEY("NIRS") OR ' + \ 'TITLE-ABS-KEY("near-infrared spectroscopy") ) AND ' + \ 'SRCTYPE("j" ) AND DOCTYPE("ar") AND SUBJAREA("NEUR") AND ' + \ 'PUBYEAR > 2018 AND PUBYEAR < 2020' for Scropus. 

The search is limited to the 500 articles published since 2019 to include the latest research results. The goal of the search is to find a unique definition for bad channels and thus to find the basis for an automatic extraction of these channels. 

The papers are checked according to their method section whether they define in this noisy- or bad-Channel. From each review we extract the criterion that defines a bad channel in their view. In addition, the number of channels as well as the channels discarded and their percentage are recorded. The design of the fNIRS is taken into account in order to comprehend the selection of rejected channels based on neurofeedback. To evaluate the criteria, chromophores are stored which provide the basis for filtering channels. In order to guarantee the stability of the criteria, the number, age, gender and the age group (adult,child,infents) of the participants are listed. 
