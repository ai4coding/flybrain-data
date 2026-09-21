# flybrain-data

Brain circuit files for the free educational block-coding extension "Fly Electronic Brain Lab" of BrixelAI (https://ai4coding.github.io).

## Source and attribution

- Connectome: FlyWire public release v783 - Dorkenwald et al. 2024 (Nature 634:124-138), Schlegel et al. 2024 (Nature 634:139-152). License CC BY-NC 4.0.
- Model: Shiu et al. 2024 (Nature 634:210-219), code https://github.com/philshiu/Drosophila_brain_model (MIT).

## Changes made

- Neurons were selected from the whole-brain model: every neuron that fired, or came within 2 mV of threshold, in a wide sweep of stimulus conditions (packs: fly, reflex).
- Connections that leave the selected set were removed (a "closed" circuit pack). A pack therefore differs from the whole-brain model; the measured agreement on held-out conditions is published in `v783/index-2.json` under `packs.<name>.validation`.
- For the pack(s) fly, sweep runs in which the whole-brain model entered global ignition (thousands of neurons recruited at once) were left out when choosing the neurons; those packs do not reproduce that state. The excluded runs are listed under `validation.ignitionExcluded`.
- The data was converted to a compact binary format (FBZ1).
- The mapping from student-facing inputs (0-100) to stimulation rates, and from neuron firing to action strength, was designed by people. Visual inputs are injected at an intermediate stage of the visual system (visual projection neurons), not at photoreceptors.

## Non-commercial

These files are for non-commercial educational use.
