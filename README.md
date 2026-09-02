# Kiarash Kasbi

**MSc Medical Biotechnology | Computational Pathology | Serial Histology Registration | 3D Tissue Reconstruction**

I am an MSc Medical Biotechnology student at the University of Padua with a **BSc background in Cellular and Molecular Biology**, working at the intersection of tissue biology, computational pathology, biomedical image analysis, and scientific visualization.

My current thesis work focuses on turning serial histology sections and semantic tissue predictions into a spatially coherent, auditable, and interpretable 3D representation.

## Current Research Focus

- Whole-slide and serial-section histology registration
- Registration quality control and failure-aware stack construction
- Semantic 3D tissue reconstruction
- Quantitative spatial analysis of reconstructed tissue classes
- Connected components, persistence, inter-class adjacency, topology, and skeleton-based descriptors
- Class-separated scientific and presentation geometry
- Interactive biomedical visualization
- Reproducible scientific software and visualization workflows

## Thesis Workflow

At a public, non-sensitive level, the workflow can be summarized as:

```text
serial histology sections
→ registration and quality control
→ aligned section stack
→ semantic label reconstruction
→ quantitative 3D spatial analysis
→ class-separated 3D representations
→ interactive scientific inspection
```

The work treats registration, reconstruction, quantitative analysis, and visualization as separate but connected scientific layers. Quantitative measurements remain tied to source-derived label volumes, while cleaned or smoothed geometry is treated as presentation-only.

## Current Software Direction

I am also developing a standalone scientific viewer for prepared 3D histology reconstructions. The current workflow supports:

- independent class visibility and opacity,
- non-destructive clipping,
- display-only smoothing,
- scientific-original versus presentation display modes,
- reproducible camera and visualization state,
- screenshot export, and
- handoff of visualization state to DCC/rendering environments.

My current viewer work is centered on validated NESTOR-derived reconstruction packages rather than arbitrary raw-data import.

## Public Portfolio

- [Whole-Slide Histology Registration and 3D Reconstruction Portfolio](https://github.com/kiarashkasbi/histology-registration-portfolio)

The portfolio is intentionally a **methodology portfolio**, not a data-release repository. It documents public-safe concepts around registration, 3D reconstruction, spatial analysis, visualization, validation, and reproducibility without publishing private thesis material or unpublished results.

## Background

**Biology and biomedical science:** Cellular and Molecular Biology, molecular biology, cancer biology, genomics, epigenetics, protein engineering, pharmacogenomics, PCR methodology, and translational medicine.

**Computational pathology:** image preprocessing, whole-slide handling, serial-section registration, tissue-mask logic, quality control, semantic volume reconstruction, and quantitative spatial analysis.

**3D and visualization:** 3D Slicer, ParaView, Maya, Blender, V-Ray, PyVista/VTK, interactive inspection, clipping, class-based visualization, and scientific presentation.

## Tools And Environments

Python, OpenCV, OpenSlide, SimpleITK, NumPy, SciPy, pandas, scikit-image, QuPath, Fiji/ImageJ, 3D Slicer, ParaView, PyVista, VTK, PySide6/Qt, Maya, Blender, V-Ray, and Unreal Engine.

## Public-Safety Boundary

My public repositories do not publish private thesis datasets, patient/sample identifiers, unpublished figures, real thesis volumes or meshes, local file paths, credentials, private laboratory material, or original private implementation code. Detailed research material is shared only when appropriate and with the relevant approval.

## Contact

- GitHub: [kiarashkasbi](https://github.com/kiarashkasbi)
- LinkedIn: [linkedin.com/in/kiarash-kasbi](https://www.linkedin.com/in/kiarash-kasbi)
- Email: kiarashkk2000@gmail.com
