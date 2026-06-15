# PR-FFL-MPI

Dataset of multi-angle FFL system.

All experiments were conducted under a selection-field gradient of **4 T/m/μ₀** using a dual-frequency excitation scheme, consisting of:

- High-frequency drive field: **30 mT/μ₀ @ 10 kHz**
- Low-frequency component: **5 mT/μ₀ @ 500 Hz**

2D imaging was carried out with spatial sampling ranges of **−9 mm to 9 mm** along both directions and a step size of **1 mm**, resulting in a system matrix of size **19 × 19**.

The sampling rate was set to **2.5 MS/s**, and the signal acquisition time for each measurement was **1 s**.

---

## Calibration Measurements

| Study | Experiment Number | Tracer | Grid |
|---------|---------|---------|---------|
| calibration | 1 | Synomag-D | 19 × 19 |
| calibration | 2 | Perimag | 19 × 19 |

---

## Phantom Measurements

| Study | Experiment Number | Tracer |
|---------|---------|---------|
| phantom | A | Synomag-D |
| phantom | C | Synomag-D |
| phantom | S | Synomag-D |

---

## Dataset Structure

```text
PR-FFL-MPI/
├── calibration/
│   ├── experiment_1_synomagD/
│   └── experiment_2_perimag/
├── phantom/
│   ├── phantom_A/
│   ├── phantom_C/
│   └── phantom_S/
└── README.md
```

---

## Experimental Parameters

| Parameter | Value |
|------------|------------|
| Selection-field gradient | 4 T/m/μ₀ |
| Drive field amplitude | 30 mT/μ₀ |
| Drive field frequency | 10 kHz |
| Low-frequency component | 5 mT/μ₀ |
| Low-frequency frequency | 500 Hz |
| Imaging range | −9 mm to 9 mm |
| Step size | 1 mm |
| System matrix size | 19 × 19 |
| Sampling rate | 2.5 MS/s |
| Acquisition time | 1 s |

---

## Available Data

### Calibration Data

- Synomag-D system matrix measurement
- Perimag system matrix measurement

### Phantom Data

- Phantom A measurement
- Phantom C measurement
- Phantom S measurement

---

## Coming Soon

🚧 **Full dataset coming soon!**

Complete raw signal data for the system matrix and phantom measurements will be made publicly available in a future release.
