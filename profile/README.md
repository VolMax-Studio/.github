# VolMax Studio Lab

**Independent verification for battery and energy-system ML.**
Power electronics + domain-grounded machine learning. We don't build your model — we
check whether its numbers survive contact with data they haven't seen.

---

### What we do

Most battery state-of-health and remaining-useful-life models are graded by the team that
built them. That conflict of interest is why a model reporting 98% accuracy in the lab can
collapse on a new cell. VolMax is the independent check: leakage detection, metric-integrity
audits, physical-consistency verification, and uncertainty calibration — on batteries,
power signals, transformers, PV, and grid data.

Independence is the product. We do not sell a competing model, so we have no incentive to
flatter a number.

---

### The method → [P10 Verification Method](https://github.com/VolMax-Studio/Battery_Health_Portfolio/blob/main/P10_method_public.md)

Every finding here is produced by one procedure: reduce to first principles → hunt
interpretation artifacts (leakage, inflation, curation) → compare to state of the art →
deliver a reproducible verdict. The caveat is the mechanism: each correction comes from a
constraint that narrows an overclaim. We apply it to our own work first.

---

### Start here

| Repository | What it is |
|---|---|
| **[Battery_Health_Portfolio](https://github.com/VolMax-Studio/Battery_Health_Portfolio)** | The flagship. NASA PCoE + Severson/Attia, DOI-archived. Honest findings led by their limits; every number regenerates from `reproduce.py`. Includes the worked example where we caught our own pipeline overclaiming three times. |
| **[Power_Signal_Tools_Portfolio](https://github.com/VolMax-Studio/Power_Signal_Tools_Portfolio)** | Verified signal-processing library (RMS, THD, DWT, Hilbert), test-covered. The measurement layer the audits stand on. |
| **[Transformer_Health_Portfolio](https://github.com/VolMax-Studio/Transformer_Health_Portfolio)** | Hierarchical DGA fault diagnosis, with tested boundaries. |
| **[PV_Anomaly_Detection](https://github.com/VolMax-Studio/PV_Anomaly_Detection)** | PV fault detection on real NREL data + injected benchmarks, honestly framed. |
| **[Data_Center_Efficiency](https://github.com/VolMax-Studio/Data_Center_Efficiency)** | The "PUE Loophole" audit — how PSU conversion losses mask real facility savings. |


---

### What we publish vs. what stays private

We publish methods, principles, and worked examples on **public datasets** — that's the
proof of competence that replaces a CV. Client data, client-specific code, and paid
audit deliverables stay private. A verifier nobody can check is a verifier nobody hires.

---

*Physics doesn't lie. Sensors don't lie. We stand at the gap between the measurement and
the claim, and check the rest.*

**VolMax Studio Lab d.o.o.** · Serbia · independent energy-ML verification
