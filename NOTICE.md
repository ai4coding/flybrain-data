# flybrain-data

Brain circuit files for the free educational block-coding extension "Fly Electronic Brain Lab" of BrixelAI (https://ai4coding.github.io).

## Source and attribution

- Connectome: FlyWire public release v783 - Dorkenwald et al. 2024 (Nature 634:124-138), Schlegel et al. 2024 (Nature 634:139-152). License CC BY-NC 4.0.
- Model: Shiu et al. 2024 (Nature 634:210-219), code https://github.com/philshiu/Drosophila_brain_model (MIT).

## Changes made

- Neurons were selected from the whole-brain model: every neuron that fired, or came within 2 mV of threshold, in a wide sweep of stimulus conditions.
- Connections that leave the selected set were removed (a "closed" circuit pack). The pack therefore differs from the whole-brain model; the measured agreement is published in `v783/index-1.json` under `validation`.
- The data was converted to a compact binary format (FBZ1).
- The mapping from student-facing inputs (0-100) to stimulation rates, and from neuron firing to action strength, was designed by people.

## Non-commercial

These files are for non-commercial educational use.
