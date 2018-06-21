# Motivation

- Defect free mechanisms synthesis
  - Produce Defect free linkages, which are the only onces useful for practical
    applications.

- Prolific Concept Generation
  - Generate as many concepts as possible to accomodate for other design
    constraints, which are out of scope of synthesis and identified in later
    stages.

- Data Driven Synthesis
  - Exploiting data for faster and intelligent solutions.

- Scalable Approach
  - The approach should be readily scalable to linkages with more number of
    links, i.e. six-bar.

# Limitations of Current Methods

  - Methods based on precision position synthesis only, do not account for the
    changes in circuit or branch of the fourbar,  resulting in solutions with
    defect and the ones that do, employ evolutionary algorithms for
    optimizations, which tend to be slow and produces few solutions.

  - Fourier-based path synthesis method do exists, but they are exclusively
    limited to four-bar linkage synthesis.

  - Other Atlas-based methods do not facilitate partial matching of the curves,
    instead they store all possible partial segments of a curve,
    which severly impact the storage efficiency.
    - in p-type descriptor paper its says, '1360 partial curves are created for each linkage sample'
