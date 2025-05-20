## Description of supplementary data for Edmonsond & Dyer: "Timing and magnitude of the Lomagundi carbon isotope excursion"

The posterior inference results (NetCDF4 files), along with Jupyter notebooks required to reproduce our results and figures, are archived on Zenodo: <https://doi.org/10.5281/zenodo.15460760>

Supplementary data are provided as .csv files; all data also are compiled in ``paleoproterozoic_database.xlsx``. All ``.pkl`` files included in this directory are calculated values that are accessed in the Jupyter notebooks.

### summary_d13C_curve.csv
Summary statistics for Paleoproterozoic d13C curve; time resolution is 1 Myr.

### paleoproterozoic_section_metadata.csv
Metadata for each section in the Paleoproterozoic d13C database. Includes section priority levels, geologic units, latitude/longitude, availability of different types of geochemical proxy data, whether each section was subsampled, and other relevant information about the stratigraphy. This information includes whether sample superposition relationships and/or heights are known and whether sedimentation rates should be calculated within each section (and if so, where the section should be split when making these calculations). Sections that were included in a 'composite section' (constructed by manually stacking separate sections through different formations) also are identified; these sections are assigned to priority level 4 (while the composite sections are assigned to priority level 1) so that duplicate sections are not included in the inference.

### paleoproterozoic_data.csv
Compiled geochemical data for stratigraphic sections tabulated in ``paleoproterozoic_section_metadata.csv``.

### paleoproterozoic_ages.csv
Compiled age constraints for stratigraphic sections tabulated in ``paleoproterozoic_section_metadata.csv``.

### diamictite_compilation.csv
Compilation of Paleoproterozoic glacial diamictite units. Includes unit names, depositional or maximum and minimum geochronological age constraints, maximum and minimum posterior ages (for units whose age is constrained by the d13C inference), stratigraphic relationships with sections in  ``paleoproterozoic_section_metadata.csv``, and references. 

### sulfur_summary.csv
Compilation of sulfur isotope fractionation observations for Paleoproterozoic geologic units. Includes unit names, type of fractionation (mass-dependent, mass-independent, or mixed), depositional or maximum and minimum geochronological age constraints, maximum and minimum posterior ages (for units whose age is constrained by the d13C inference), and stratigraphic relationships with sections in ``paleoproterozoic_section_metadata.csv``.




