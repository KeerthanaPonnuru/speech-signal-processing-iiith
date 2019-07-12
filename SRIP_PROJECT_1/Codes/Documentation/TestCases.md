# Experiment Project Documentation
---
## Introduction
This document captures the test cases of the experiment.

## Functional Test Cases
| Test case Id | Test Scenario | Test Case | Test Steps | Test Data | Expected Output | Actual Output | Test Result | Comments |
| ---  |---    |---            |---   | ---      |  ---           |---   | ---      |  ---           |
| 1. | Open HTML in the browser|1.Running the Stimulation| 1.Install the prerequisites 2. Run the experiment |Use the required buttons| The corresponding webpage opens | The respective page is be displayed on the screen | Pass | None |


| 2. | Instructions for the website | Understanding the running  | 1. Open Instructions | Checked the Instrucions based on Windows/Linux/MAC user | The instructions are displayed| The instructions are displayed  | Pass | Make sure tone.js and npm are installed |


| 3. |In-built audio for Waveform button |Click on the corresponding button| 1. Select "1" button 2. Select Play/Pause/Stop ad required|Waveform is displayed|Waveform corresponds to in-built audio | Waveform corresponds to in-built audio | Pass | None|


| 4. |Aliasing and Quantization|Click on the corresponding button|1.Select "2" button 2.Select Play 3.Adjust Tempo 4.Select required Bits/Sampling|The simulation runs| Simulation should run as per mentioned functionalitty|Simulation runs as given| Pass |None|

| 5. |FilterDesign|Click on the corresponding button|1.Select "3" button 2.Choose the graph display 3.Adjust Partial Count |The simulation runs| Simulation should run as per mentioned functionalitty|Simulation runs as given| Pass |None|

| 6. |Waveform|Click on the corresponding button|1.Select "4" button 2.Select start to begin 3.Select stop to pause|The simulation runs| Simulation should run as per mentioned functionalitty|Simulation runs as given| Pass |None|

## Cross Browser Testing
| S.no | Browser | Version | Works ( Yes / No ) |
| ---  |---    |---            |---   |
| 1. | Chrome | 75 | Yes |
| 2. | Chrome | 74 | Yes |
| 3. | Chrome | 73 | Yes |
| 4. | Firefox | 67 | Yes |
| 5. | Firefox | 66 | Yes |
| 6. | Safari | 12.1 | Yes |
| 7. | Edge | 17 | Yes |
| 8. | Edge | 18 | Yes |
