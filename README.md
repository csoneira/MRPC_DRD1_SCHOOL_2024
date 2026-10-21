# MRPC DRD1 School 2024

Teaching material for **Lab 6.B: MRPC Characterization** at the **DRD1 Gaseous Detectors School**, CERN, 27 November–6 December 2024.

**Tutor and exercise author:** Cayetano Soneira Landín

This repository contains an exercise that I prepared and proposed to the school participants while serving as a tutor. It is teaching material for the practical session, not a record of an exercise completed by me as a student.

## Contents

- [`MRPC_DRD1_LAB.ipynb`](MRPC_DRD1_LAB.ipynb): guided analysis notebook used for the practical session.
- `DATA/processed_events.txt`: processed event sample used by the exercise.
- `DATA/processed_events_vertical_track.txt`: processed vertical-track event sample.

The detector-control documentation used during the session is available on the [miniTRASGO detector page](http://nuc1.fis.ucm.es/minitrasgo/).

## Exercise scope

The practical exercise guides participants through the characterization of a four-plane MRPC mini-telescope. The analysis includes:

- detector efficiency as a function of high voltage;
- charge spectra and charge calibration;
- background rate and streamer probability;
- timing calibration and time-resolution studies;
- position and angular-distribution plots.

The repository includes pre-collected data so that the analysis can also be performed independently of the detector setup.

## Notebook

The notebook is intended to be run interactively, including from Google Colab:

[Open `MRPC_DRD1_LAB.ipynb` in Google Colab](https://colab.research.google.com/github/csoneira/MRPC_DRD1_SCHOOL_2024/blob/main/MRPC_DRD1_LAB.ipynb)

When using Colab, make the `DATA/` directory available to the notebook as described in the exercise.

## References

- *Performance of the HADES ToF Wall Front-End Electronics*. DOI: [10.1109/TNS.2010.2056928](https://doi.org/10.1109/TNS.2010.2056928)
- *TRB3: High Precision TDC Platform*. DOI: [10.1088/1748-0221/8/12/C12043](https://doi.org/10.1088/1748-0221/8/12/C12043)
