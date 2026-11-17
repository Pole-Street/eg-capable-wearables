This database contains raw data, transformed to WFDB format, generated using a Patient Simulator, the METRON PS-440, and measured with 5 different devices: (1) hospital electrocardiograph model Philips TC30; (2) Apple Watch Series 9; (3) Samsung Galaxy Watch 6; (4) Fitbit Sense 2; and (5) Withings ScanWatch.

The database is organised using a directory for each device:

  1. philips_tc30 directory: Raw data in WFDB format for the Philips TC30 hospital electrocardiograph. The recordings last 11 seconds, include 12 leads and have a sampling rate of 500 Hz.
  2. applewatch_serie9 directory: Raw data in WFDB format for Apple Watch Series 9. The recordings last 30 seconds and correspond to Lead I, with a sampling rate of 512 Hz.
  2. samsunggalaxy6 directory: Raw data in WFDB format for the Samsung Galaxy Watch 6. The recordings last 30 seconds and correspond to Lead I, with a sampling rate of 500 Hz.
  2. fitbitsense2 directory: Raw data in WFDB format for the Fitbit Sense 2. The recordings last 30 seconds and correspond to Lead I, with a sampling rate of 250 Hz.
  2. withingsscanwatch directory: Raw data in WFDB format for Withings ScanWatch. The recordings last 30 seconds and correspond to Lead I, with a sampling rate of 300 Hz.

For each device the database contains the following records, all experiments in quintuplicate:

  - amp_test 4 experiments:
    - amp500: records amp500_0 to amp500_4 corresponding to an ECG signal of 500µV amplitude.
      ...
    - amp2000: records amp2000_0 to amp2000_4 corresponding to an ECG signal of 2000µV amplitude.

  - freq_test 15 experimentos:
    - f30: records f30_0 to f30_4 corresponding to a 30 BPM ECG signal.
      ...
    - f300: records f300_0 to f300_4 corresponding to a 300 BPM ECG signal.

  - sqr-2hz: sqr-2hz_0 to sqr-2hz_4 registers corresponding to a square wave signal with a frequency of 2 Hz.

  - st-segment 16 experiments:
    - st-m8: st-m8_0 to st-m8_4 records corresponding to an ECG signal with ST-segment depression of -800µV.
    ...
    - st-p8: st-p8_0 to st-p8_4 records corresponding to an ECG signal with ST-segment elevation of +800µV.

The database contains a total of 900 records.