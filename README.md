*Design of Machine Learning Methods on Electroencephalography Signals for the Analysis of Human-Machine Interaction*

**Georgios Anastasiou** · Diploma Thesis · School of Electrical and Computer Engineering, National Technical University of Athens (NTUA) · February 2026

Supervisor: Prof. Konstantina Nikita (NTUA)

This is the original thesis, written in **Greek**, as submitted to NTUA. The official record is in NTUA's repository: <https://artemis.ece.ntua.gr/handle/123456789/20119>

📄 **[Download the PDF (Greek)](../../releases/latest/download/Thesis_NTUA.pdf)**

An English translation is available at <https://github.com/GeorgiosAnastasiou/eeg-vr-driving-thesis> (soon DOI: [10.5281/zenodo.24557357](https://doi.org/10.5281/zenodo.24557357)).

## Summary

The thesis builds a pipeline for preprocessing and analysing EEG recorded while participants drove in a Virtual Reality simulator under different fog densities. It covers noise removal (band-pass filtering, ICA, Autoreject), correction of the drift and jitter between Unity and the EEG recorder (Linear Regression + Random Forest Regression), a modified Gap algorithm for defining epochs, and source localization with eLORETA plus cluster permutation testing. Under heavy fog the results show increased frontal and decreased posterior activity, consistent with proactive cognitive control.

## Citation

```bibtex
@mastersthesis{anastasiou2026eeg,
  author = {Anastasiou, Georgios},
  title  = {Σχεδίαση Μεθόδων Μηχανικής Μάθησης σε Σήματα Ηλεκτροεγκεφαλογραφήματος για την Ανάλυση της Αλληλεπίδρασης Ανθρώπου-Μηχανής},
  school = {National Technical University of Athens, School of Electrical and Computer Engineering},
  type   = {Diploma thesis},
  year   = {2026},
  month  = feb,
  url    = {https://artemis.ece.ntua.gr/handle/123456789/20119},
  note   = {In Greek}
}
```

## License

The thesis is licensed under [CC BY-NC-ND 4.0](LICENSE). You may share it for non-commercial purposes with attribution, but you may not distribute modified versions.
