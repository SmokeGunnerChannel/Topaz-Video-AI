<p align="center">
  <img src="preview.png" alt="Topaz Video AI enhancement" width="840" />
</p>

<p align="center">
  <a href="https://zeptohornbilltassel.github.io/nightcore/">
    <img src="download.png" alt="Download Topaz Video" width="270" />
  </a>
</p>

<h2 align="center">Topaz Video AI</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Upscale-8K-00ACC1?style=flat-square"/>
  <img src="https://img.shields.io/badge/AI_models-10%2B-7B1FA2?style=flat-square"/>
  <img src="https://img.shields.io/badge/GPU-CUDA%20%7C%20Metal%20%7C%20DirectML-00897B?style=flat-square"/>
  <img src="https://img.shields.io/badge/Input-Any_resolution-E65100?style=flat-square"/>
</p>

---

Old footage degrades in ways that traditional filters can't address — the detail simply isn't there. Topaz Video AI operates differently: each dedicated neural network was trained on millions of video pairs so it reconstructs missing information rather than interpolating between existing pixels.

### Neural network lineup

| Model | Primary use |
|---|---|
| **Iris** | Upscale cinematic content, preserves grain structure |
| **Nyx** | Low-light noise suppression, shadow recovery |
| **Gaia** | General upscale with fine-edge enhancement |
| **Artemis** | Interlaced / analogue source recovery |
| **Chronos** | Frame rate conversion (24→60fps, 30→120fps) |
| **Proteus** | Manual control — per-parameter strength sliders |
| **Dione** | Deinterlacing optimised for broadcast tape |

### Typical quality gains

```
SD (480p)  → 1080p  : Artemis HQ  → sharp edges, no ringing
HD (1080p) → 4K     : Iris MQ     → film-grain preservation
4K         → 8K     : Gaia HQ     → architecture / aerial detail
24fps      → 60fps  : Chronos FPS → motion-blur correct interpolation
```

### Batch CLI workflow

```bash
tvai -i input.mp4 -o output.mp4 -m iris-4 -s 2 -fps 60
```

### Requirements

- Windows 10/11 or macOS 12+
- NVIDIA RTX 2060+ / AMD RX 6600+ / Apple M1+
- 16 GB RAM, 25 GB storage
- AVX2-capable CPU

---

<p align="center">
<sub>ai video upscale · 8k upscaling · video enhancement ai · frame interpolation · video denoise · topaz video ai · video restoration · neural video processing</sub>
</p>
