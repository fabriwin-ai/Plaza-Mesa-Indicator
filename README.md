# Affordable Production-Ready Dopamine Indicator

A browser-based, sensor-driven visualization built around the **React · Observe · Learn · Behave (ROLB)** loop. It combines live camera motion and microphone input with filtering, XOR feature fusion, and an evolving 2.5D grid.

## Features

- Live microphone and camera input, with on-screen sensor and activity indicators.
- FIR and IIR filtering controls and XOR feature fusion.
- Energy, XOR field, wave, and cellular grid modes.
- Configurable grid size, decay, sensor gain, and neuromorphic batch behavior.
- Audio controls and presets for calm, reactive, chaotic, filter, and neuromorphic behavior.
- A single self-contained HTML file; no build step or third-party libraries are required.

## Run

Open `index.html` in a modern browser. The browser will ask for camera and microphone access when you select **Grant Sensors & Start**. Camera and microphone APIs generally require a secure context, such as `https://` or `localhost`; if opening the file directly does not work in your browser, serve this folder locally and open it through `localhost`.

The page uses camera and microphone streams locally for the live visualization. The project does not store or transmit sensor data.

## Controls

Use the panel to toggle the ROLB phases, adjust sensor gain and filtering, choose a grid mode, or apply a preset. The audio controls shape the visualization response; they do not play or record audio.

## License

Released under the [MIT License](LICENSE).


