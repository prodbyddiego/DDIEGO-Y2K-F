# DDIEGO Y2K FX — GitHub Build

This repository is a JUCE VST3 plugin project designed to build automatically with GitHub Actions.

## Build online
1. Create a GitHub repository.
2. Upload the contents of this folder.
3. Open **Actions**.
4. Select **Build VST3**.
5. Click **Run workflow**.
6. When finished, download the artifact named `DDIEGO-Y2K-FX-VST3`.
7. Extract it and install the `.vst3` file in your DAW's VST3 folder.

## Important
This version is a compilable VST3 scaffold. The GUI and engine architecture are included, but the complete drag-and-drop sample loader, waveform rendering, true granular sampler and slice playback still need to be implemented as the next development step.

The workflow downloads JUCE automatically, so JUCE does not need to be installed on the computer running the build.
