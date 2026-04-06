# OFDM Signal Simulator

An interactive, browser-based **OFDM (Orthogonal Frequency Division Multiplexing)** simulator built for learning and experimentation. No installation required — runs entirely in your browser.

## Live Demo

**[Open the Simulator](https://miladzarour.github.io/OFDM-Simulator/ofdm_simulator.html)**

---

## What Can You Do?

- Visualize OFDM subcarriers, constellations, and bit error rates in real time
- Adjust modulation order (BPSK, QPSK, 16-QAM, 64-QAM, 256-QAM)
- Simulate real-world channel effects: AWGN, multipath fading, Doppler shift, and CFO
- Enable Forward Error Correction (FEC) with repetition or convolutional coding
- Compare BER curves across all modulations at once
- Transmit and receive images through the simulated channel
- Explore interactive educational demos:
  - **Fourier Transform Playground** — draw signals, see their FFT live
  - **CFO / ICI Demo** — visualize inter-carrier interference
  - **FEC Demo** — see coding gain on BER curves
- Download a full **Math Report** (equation sheet) for the current simulation

---

## Features

| Feature | Details |
|---|---|
| Modulations | BPSK, QPSK, 16/64/256-QAM |
| Channel Models | AWGN, Multipath, Doppler, CFO |
| FEC Coding | Rate-1/3 repetition, Rate-1/2 convolutional (Viterbi) |
| FFT Size | 64 / 256 / 1024 subcarriers |
| Stats | Shannon capacity, spectral efficiency, PAPR, EVM |
| Export | Save charts as PNG, download Math Report |

---

## How to Use

1. Click the **[Live Demo](https://miladzarour.github.io/OFDM-Simulator/ofdm_simulator.html)** link above
2. Adjust parameters in the left sidebar
3. Watch the four visualization panels update in real time
4. Try the educational demos from the buttons in the sidebar
5. Use keyboard shortcuts: `Space` = run sim, `B` = BER curve, `C` = compare all mods

---

## Topics Covered

OFDM fundamentals · FFT/IFFT · Cyclic prefix · Multipath channels · Doppler fading · Carrier frequency offset (CFO) · Inter-carrier interference (ICI) · QAM/PSK modulation · BER analysis · Shannon capacity · Forward error correction · Viterbi decoding

---

*Built as an educational tool for telecommunications engineering.*
