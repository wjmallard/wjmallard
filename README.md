I'm a scientist and engineer with 20 years of experience building systems for computational biology, genomics, real-time signal processing, machine learning, and computer vision. Here are some of the things I've built over the years.

My full portfolio, including publications and earlier work, is at [wjmallard.net](https://wjmallard.net/portfolio.html).

## Computational Biology

During my PhD at Harvard, I built machine learning pipelines for protein structure analysis, and computer vision pipelines for live-cell microscopy.

- [**alphafold-contact-clustering**](https://github.com/wjmallard/alphafold-contact-clustering) (2025) — AlphaFold ensemble analysis: construct contact maps via K-d tree, identify protein binding modes via unsupervised clustering (Python)
- [**MeshCell**](https://github.com/wjmallard/MeshCell) (2020) — Computer vision and computational geometry pipeline for automated analysis of cell size and shape (Python)
- [**z-ring-treadmilling**](https://github.com/wjmallard/z-ring-treadmilling) (2022) — Particle tracking and motion analysis: trajectory extraction, MSD fitting, velocity estimation (Python, Fiji/Jython)
- [**z-ring-constriction**](https://github.com/wjmallard/z-ring-constriction) (2023) — Time-series image processing: calibration, registration, object tracking, constriction rate measurement (Python, Fiji/Jython)
- [**PyLSF**](https://github.com/wjmallard/PyLSF) (2013) — Python C extension for HPC cluster job management via the IBM LSF API (C, Python)

## Real-time Signal Processing

Before my PhD, I spent several years at UC Berkeley building FPGA-based astronomy instruments, and contributing to CASPER, an open-source signal processing platform used by observatories around the world.

- [**isi-digital-backend**](https://github.com/wjmallard/isi-digital-backend) (2010) — 138 Gbps FX correlator on 3 Virtex-5 FPGAs, for the Infrared Spatial Interferometer at Mount Wilson Observatory (Simulink, C, Python)
- [**gpu-xengine**](https://github.com/wjmallard/gpu-xengine) (2026) — GPU cross-correlator for a 3-telescope interferometer (CUDA, C++)
- [**xgb_recv**](https://github.com/wjmallard/xgb_recv) (2008) — 10 GbE UDP receiver with synchronized ring buffer; core architecture adopted into PySPEAD, the data transport layer for the Square Kilometre Array (C)
- [CASPER library commits](https://github.com/casper-astro/mlib_devel/commits?author=wjmallard) (2008–2011) — 60+ commits to the CASPER FPGA library (Simulink, Matlab)

## Data Archaeology

Since completing my PhD, I've been building full-stack tools to archive and explore my own data — personal projects I never had time for in grad school.

- [**claude-conversations**](https://github.com/wjmallard/claude-conversations) (2026) — An offline browser and search engine over an archive of exported Claude conversations. (Python, PostgreSQL, Flask)
- [**twitter-screenshot-archive**](https://github.com/wjmallard/twitter-screenshot-archive) (2026) — Search engine over Twitter screenshots. OCR ingest pipeline, full-text and semantic search (pgvector), MinHash near-duplicate detection, PCA/HDBSCAN topic clustering, temporal analysis, and an MCP server for LLM tool use. (Python, PostgreSQL, Flask)
- [**location-history**](https://github.com/wjmallard/location-history) (2025) — Personal location history explorer: imports Google Timeline data into PostGIS, with local reverse geocoding against OSM boundaries, trip detection, and an interactive map UI for spatial and temporal queries. (Python, PostgreSQL/PostGIS, Flask)
- [**sensor-log**](https://github.com/wjmallard/sensor-log) (2026) — Automated collection of environmental data from Bluetooth sensors (temperature, humidity, pressure, CO2 levels), with a web dashboard and reverse-engineered BLE readers for the sensor hardware. (Python, PostgreSQL/TimescaleDB, Flask, Swift)

## Side Quests

- [**JScreenSaver**](https://github.com/wjmallard/jscreensaver) \[[live](https://jscreensaver.net)\] (2026) — JavaScript port of generative artwork from [XScreenSaver](https://www.jwz.org/xscreensaver/) (by Jamie Zawinski & contributors). 170+ Unix/X11 screenhacks reimplemented from the original C and OpenGL. Minimalist full-viewport UI with keyboard navigation and mobile support. (JavaScript, Canvas 2D, WebGL/GLSL, three.js)
- [**offline-maps**](https://github.com/wjmallard/offline-maps) (2026) — An offline map viewer that makes *zero* network requests at runtime. Includes a demo dataset: a layer with every automated license-plate reader (ALPR) known to OpenStreetMap. (Python, Flask, MapLibre GL, GeoPandas)
- [**adsb-fingerprint**](https://github.com/wjmallard/adsb-fingerprint) (2026) — RF fingerprinting of ADS-B transponders. Uses a cheap software-defined radio (RTL-SDR) to detect and demodulate Mode S signals, and runs them through a convolutional neural network to identify the physical airframe from raw IQ samples. The network still works with the airframe's ID bits masked out, and still beats chance on the 8 µs Mode S preamble alone — a waveform every transponder transmits identically by spec. Also displays a live map of what's overhead. (Python, PyTorch, PostgreSQL, Flask, MapLibre GL)
