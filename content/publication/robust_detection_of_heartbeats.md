+++
abstract = "Backgrounds: The heartbeat is fundamental cardiac activity which is straightforwardly detected with a variety of measurement techniques for analyzing physiological signals. Unfortunately, unexpected noise or contaminated signals can distort or cut out electrocardiogram (ECG) signals in practice, misleading the heartbeat detectors to report a false heart rate or suspend itself for a considerable length of time in the worst case. To deal with the problem of unreliable heartbeat detection, PhysioNet/CinC suggests a challenge in 2014 for developing robust heart beat detectors using multimodal signals. Methods: This article proposes a multimodal data association method that supplements ECG as a primary input signal with blood pressure (BP) and electroencephalogram (EEG) as complementary input signals when input signals are unreliable. If the current signal quality index (SQI) qualifies ECG as a reliable input signal, our method applies QRS detection to ECG and reports heartbeats. Otherwise, the current SQI selects the best supplementary input signal between BP and EEG after evaluating the current SQI of BP. When BP is chosen as a supplementary input signal, our association model between ECG and BP enables us to compute their regular intervals, detect characteristics BP signals, and estimate the locations of the heartbeat. When both ECG and BP are not qualified, our fusion method resorts to the association model between ECG and EEG that allows us to apply an adaptive filter to ECG and EEG, extract the QRS candidates, and report heartbeats. Results: The proposed method achieved an overall score of 86.26 % for the test data when the input signals are unreliable. Our method outperformed the traditional method, which achieved 79.28 % using QRS detector and BP detector from PhysioNet. Our multimodal signal processing method outperforms the conventional unimodal method of taking ECG signals alone for both training and test data sets. Conclusions: To detect the heartbeat robustly, we have proposed a novel multimodal data association method of supplementing ECG with a variety of physiological signals and accounting for the patient-specific lag between different pulsatile signals and ECG. Multimodal signal detectors and data-fusion approaches such as those proposed in this article can reduce false alarms and improve patient monitoring."
authors = ["Taegyun Jeon", "Jongmin Yu", "Witold Pedrycz", "Moongu Jeon", "Boreom Lee", "Byeongcheol Lee"]
date = "2016-01-15T01:26:13+09:00"
publication = "In *Biomedical Engineering Online (BME)*"
title = "Robust Detection of Heart Beats using Association Models from BP and EEG signals"
url_code = ""
url_dataset = "http://physionet.org/physiobank/database/challenge/2014/"
url_image = ""
url_pdf = "http://biomedical-engineering-online.biomedcentral.com/track/pdf/10.1186/s12938-016-0122-0?site=biomedical-engineering-online.biomedcentral.com"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = " Link"
url = "http://biomedical-engineering-online.biomedcentral.com/articles/10.1186/s12938-016-0122-0"

[[url_custom]]
name = " BibTex"
url = "/bib/jeon2016robust.bib"

+++

