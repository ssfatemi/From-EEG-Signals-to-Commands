# MI-BCI Datasets

This folder provides links and brief descriptions of publicly available EEG datasets commonly used for **motor imagery brain-computer interface (MI-BCI)** research, including conventional machine-learning, deep-learning, transfer-learning, and cross-subject/cross-session studies.

---

## 1. BCI Competition IV — Dataset 2a

**Official dataset:**\
[https://www.bbci.de/competition/iv/desc\_2a.html](https://www.bbci.de/competition/iv/desc_2a.html)

**Download:**\
[https://www.bbci.de/competition/iv/download/index.html](https://www.bbci.de/competition/iv/download/index.html)

A widely used **four-class motor imagery EEG dataset** from Graz University of Technology, containing recordings from 9 subjects with 22 EEG and 3 EOG channels. The four MI classes are left hand, right hand, both feet, and tongue. It is one of the most frequently used benchmark datasets for MI-BCI classification and deep learning.

---

## 2. BCI Competition IV — Dataset 2b

**Official dataset:**\
[https://www.bbci.de/competition/iv/desc\_2b.html](https://www.bbci.de/competition/iv/desc_2b.html)

**Download:**\
[https://www.bbci.de/competition/iv/download/index.html](https://www.bbci.de/competition/iv/download/index.html)

A motor imagery dataset containing **left- and right-hand imagery** recorded from 9 subjects using 3 EEG channels together with EOG channels. It is particularly useful for investigating MI classification with a **small number of EEG channels** and for cross-session evaluation.

---

## 3. BCI Competition IV — Dataset 1

**Official dataset:**\
[https://www.bbci.de/competition/iv/desc\_1.html](https://www.bbci.de/competition/iv/desc_1.html)

**Download:**\
[https://www.bbci.de/competition/iv/download/index.html](https://www.bbci.de/competition/iv/download/index.html)

A two-class motor imagery dataset containing **left-hand, right-hand, and foot imagery** recorded with 64 EEG channels from 7 subjects. The evaluation data are continuous EEG, making the dataset useful for studying classifier application and continuous MI decoding.

---

## 4. BCI Competition III — Dataset IVa

**Official dataset:**\
[https://www.bbci.de/competition/iii/desc\_IVa.html](https://www.bbci.de/competition/iii/desc_IVa.html)

**Competition page:**\
[https://www.bbci.de/competition/iii/](https://www.bbci.de/competition/iii/)

A **two-class motor imagery dataset** involving right-hand and foot imagery from 5 subjects. A major characteristic is the deliberately limited amount of training data for some subjects, making it useful for studying **small-data learning, subject transfer, and cross-subject generalization**.

---

## 5. BCI Competition III — Dataset IIIa

**Official dataset:**\
[https://www.bbci.de/competition/iii/data\_set\_iiia.html](https://www.bbci.de/competition/iii/data_set_iiia.html)

**Competition page:**\
[https://www.bbci.de/competition/iii/](https://www.bbci.de/competition/iii/)

A four-class motor imagery dataset from 3 subjects involving **left hand, right hand, foot, and tongue imagery**. It contains 60 EEG channels sampled at 250 Hz and is commonly used for multi-class MI-BCI classification.

---

## 6. PhysioNet EEG Motor Movement/Imagery Dataset

**Official dataset:**\
[https://physionet.org/content/eegmmidb/1.0.0/](https://physionet.org/content/eegmmidb/1.0.0/)

**DOI:**\
[https://doi.org/10.13026/C28G6P](https://doi.org/10.13026/C28G6P)

A large open-access EEG dataset containing **64-channel recordings from subjects performing real and imagined motor tasks**. The dataset includes unilateral and bilateral hand/foot motor imagery and movement conditions and is widely used for EEG decoding and MI-BCI research. The data are available in EDF+ format at 160 Hz.

---

## 7. High-Gamma Dataset

**MOABB dataset page:**\
[https://moabb.neurotechx.com/docs/generated/moabb.datasets.Schirrmeister2017.html](https://moabb.neurotechx.com/docs/generated/moabb.datasets.Schirrmeister2017.html)

**NEMAR dataset:**\
[https://nemar.org/dataset/nm000172](https://nemar.org/dataset/nm000172)

**Paper DOI:**\
[https://doi.org/10.1002/hbm.23730](https://doi.org/10.1002/hbm.23730)

The High-Gamma Dataset contains EEG recordings from **14 subjects using 128 electrodes at 500 Hz**, with four movement/imagery-related classes: left hand, right hand, feet, and rest. It was introduced in the work of Schirrmeister et al. and is particularly important for **deep-learning-based EEG decoding** and investigation of high-frequency EEG activity.

---

## 8. BNCI Horizon 2020 Datasets

**Official database:**\
[https://bnci-horizon-2020.eu/database/data-sets](https://bnci-horizon-2020.eu/database/data-sets)

**MOABB documentation:**\
[https://moabb.neurotechx.com/docs/dataset\_summary.html](https://moabb.neurotechx.com/docs/dataset_summary.html)

BNCI Horizon 2020 is a collection of openly available datasets covering several BCI paradigms, including numerous **motor imagery datasets**. Examples include BNCI2014-001, BNCI2014-002, BNCI2014-004, BNCI2015-001, BNCI2015-004, and BNCI2019-001. The datasets provide useful alternatives for investigating **cross-subject, cross-session, and transfer-learning performance**.

---

## 9. MOABB Dataset Collection

**Official website:**\
[https://moabb.neurotechx.com/](https://moabb.neurotechx.com/)

**Dataset summary:**\
[https://moabb.neurotechx.com/docs/dataset\_summary.html](https://moabb.neurotechx.com/docs/dataset_summary.html)

**GitHub:**\
[https://github.com/NeuroTechX/moabb](https://github.com/NeuroTechX/moabb)

MOABB (Mother of All BCI Benchmarks) is a framework that provides standardized access to a large collection of publicly available BCI datasets and enables reproducible benchmarking of EEG decoding algorithms. The current dataset catalog contains **160 curated BCI datasets and more than 3,600 subjects**.

Rather than being a single dataset, MOABB provides a convenient unified interface for accessing and benchmarking many datasets, including several of those listed in this document.

---

# Additional MI-BCI Datasets

## 10. OpenBMI

**MOABB dataset page:**\
[https://moabb.neurotechx.com/docs/generated/moabb.datasets.Lee2019\_MI.html](https://moabb.neurotechx.com/docs/generated/moabb.datasets.Lee2019_MI.html)

**MOABB:**\
[https://moabb.neurotechx.com/](https://moabb.neurotechx.com/)

The OpenBMI dataset provides EEG/EMG recordings for motor imagery experiments. The MI recordings were acquired using **62 EEG electrodes at 1,000 Hz**, with participants performing left- and right-hand grasping motor imagery. It is particularly useful for **cross-subject and cross-session MI-BCI research**.

---

## 11. GigaDB / Cho2017

**GigaDB dataset:**\
[https://gigadb.org/dataset/100295](https://gigadb.org/dataset/100295)

**MOABB implementation:**\
[https://github.com/NeuroTechX/moabb/blob/develop/moabb/datasets/gigadb.py](https://github.com/NeuroTechX/moabb/blob/develop/moabb/datasets/gigadb.py)

The Cho2017 dataset contains EEG recordings from **52 subjects** performing left- and right-hand motor imagery. Data were recorded using **64 EEG electrodes at 512 Hz**, making it a valuable relatively large-scale dataset for studying **cross-subject MI classification and generalization**.

---

## 12. BCI Competition III — Dataset IIIb

**Official competition:**\
[https://www.bbci.de/competition/iii/](https://www.bbci.de/competition/iii/)

A two-class left/right-hand motor imagery dataset specifically designed to investigate **non-stationarity**. It contains recordings from 3 subjects using only 2 bipolar EEG channels, making it useful for studying robust MI decoding under changing signal characteristics.

---

## 13. BCI Competition III — Dataset IVc

**Official competition:**\
[https://www.bbci.de/competition/iii/](https://www.bbci.de/competition/iii/)

A two-class motor imagery dataset designed to investigate the **time-invariance problem**. Training and test recordings were separated by approximately four hours, with the test data also including a relaxation condition. It is therefore useful for evaluating temporal/session generalization.

#
