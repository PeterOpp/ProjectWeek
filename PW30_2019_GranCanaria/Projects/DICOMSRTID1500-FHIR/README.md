Back to [Projects List](../../README.md#ProjectsList)

# Roundtrip conversion between DICOM SR and FHIR representations for imaging measurements

## Key Investigators

- Hans Meine (Fraunhofer MEVIS)
- Peter Oppermann (Fraunhofer MEVIS)
- Andrey Fedorov (BWH)
- Tobias Stein (DKFZ)

# Project Description

Our goal is to investigate and understand (the possibility of?) lossless, automatic,
"roundtrip" conversion between DICOM Structured Reporting and FHIR representations
for communicating imaging-derived measurements.

## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Understand and discuss capabilities of the two representations.
2. Understand possibility, limitations, support in tools for lossless interoperability
between DICOM SR TID1500 instances and FHIR documents.

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

1. Put together pointers to relevant documentation, samples, tutorials to help get started
a novice in the topic.
2. Define specific examples of varying complexity.
3. Create hand-coded or automatically generated representations of the same content
using the two approaches.

Let's use this [Repository](https://github.com/PeterOpp/tid1500-fhir) for to collect examples and code 

Should we also consider [TID2000 Basic Diagnostic Imaging Report](http://dicom.nema.org/medical/dicom/current/output/chtml/part16/chapter_A.html#sect_TID_2000)?

## Progress and Next Steps

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE. If there are specific steps that you could not complete then you can describe them here, too. -->

1. Describe specific steps you **have actually done**.
1. ...
1. ...

# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

# Background and References

<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->

Relevant FHIR resources for the diagnostic report and reported observations:
* DiagnosticReport resource: https://www.hl7.org/fhir/diagnosticreport.html
* codedDiagnosis: https://www.hl7.org/fhir/diagnosticreport-definitions.html#DiagnosticReport.codedDiagnosis
* result: https://www.hl7.org/fhir/diagnosticreport-definitions.html#DiagnosticReport.result
* image: https://www.hl7.org/fhir/diagnosticreport-definitions.html#DiagnosticReport.image
* observartion resource: https://www.hl7.org/fhir/observation.html

Other FHIR-related pointers:
* [#FHIR and confusion about the 80/20 rule](http://www.healthintersections.com.au/?p=1924), and interesting discussion on this rule in the context of DICOM: [FHIR Extensions, the 80/20 rule, DICOM and the LONG tail](http://www.healthintersections.com.au/?cat=39), by Grahame Grieve
