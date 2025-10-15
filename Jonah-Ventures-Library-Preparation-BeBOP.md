---
# MIOP terms
methodology_category: Omics Analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols
purpose: PCR [OBI:0000415], Library Preparation [OBI:0000711]
analyses: PCR [OBI:0000415], Library Preparation [OBI:0000711]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024]
environmental_medium: sea water [ENVO:00002149], polymerase chain reaction [OBI:0000415]
target: amplicon sequencing assay [OBI_0002767]
creator: 'Shannon Brown, Han Weinrich, Samantha Setta, Zachary Gold, Sean McAllister'
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], Centrifuge [OBI:0400106]
skills_required: 'sterile technique, pipetting skills, standard molecular technique'
time_required: 
personnel_required: 1
language: en
issued: '2025-05-01'
audience: 'scientists'
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
barcoding_pcr_appr: two-step pcr
pcr2_amplificationReactionVolume: 25
pcr2_commercial_mm: Promega Master mix
pcr2_dna_vol: 2
pcr2_cond: initial denaturation:95_3; denaturation:95_0.5; annealing:55_0.5; elongation:72_0.5;8
pcr2_annealingTemp: 55
pcr2_cycles: 8
pcr2_analysis_software: missing: not collected
pcr2_plate_id: missing: not collected
pcr2_method_additional: missing: not collected
sequencing_location: Texas A&M Agrilife Genomics and Bioinformatics Sequencing Core
platform: ILLUMINA
instrument: Illumina NovaSeq 6000
seq_kit: Illumina NovaSeq SP Reagent Kit v1.5 (500 cycles) (Cat_No:20028402)
lib_layout: paired end
lib_screen: 'PCR1 product was purified using an Exo1/SAP PCR Amplicon Clean Up before PCR2, then barcoded using Two-Step Barcoding PCR with Illumina Nextera Unique Dual Indices, 
cleaned and normalized with Life Technologies SequalPrep Normalization kit (cat#A10510-01), pooled using 5 µL of product quantified using a Qubit (ThermoFisher Scientific) and diluted to 800 pM before loading it onto a NovaSeq Flow Cell'
adapter_forward: TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG
adapter_reverse: GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG
lib_conc: 800
lib_conc_unit: pM
lib_conc_meth: Qubit
phix_perc: 35
checksum_method: linux md5sum
seq_method_additional: PhiX was spiked in at 35%
---

# NOAA PMEL OME Jonah Ventures Metabarcoding Library Preparation Protocol 

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for the list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|<http://orcid.org/0000-0003-0490-7630>	|2025-05-01|
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  |<https://orcid.org/0000-0001-9808-2638>|2025-05-01|
| Han Weinrich | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  |<http://orcid.org/0009-0007-6063-0986>|2025-05-01|
| Sean McAllister | Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|<http://orcid.org/0000-0001-6654-3495>|2025-05-01|
| Samantha Setta | Ocean Molecular Ecology, NOAA PMEL & UW CICOES |<https://orcid.org/0000-0001-9075-7573>|2025-10-01|


## RELATED PROTOCOLS


#### Internal Protocols
| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
|NOAA-PMEL-OME MiFish mod Universal Teleost 12S PCR Protocol | <https://doi.org/10.5281/zenodo.14834590>|v1.1| 2025-02-10|
|NOAA-PMEL-OME Kelly Metazoan 16S PCR Protocol | <https://doi.org/10.5281/zenodo.11398148>|v1.0| 2024-05-30|
|NOAA-PMEL-OME Machida Metazoan 18S V8 PCR Protocol | <https://doi.org/10.5281/zenodo.11398146>|v1.0| 2024-05-30|
|NOAA-PMEL-OME WhiteSterling Phytoplankton ITS1 PCR Protocol | <https://doi.org/10.5281/zenodo.11398140>|v1.0| 2024-05-30|
|NOAA-PMEL-OME Parada Universal 16S PCR Protocol | <https://doi.org/10.5281/zenodo.11398127>|v1.0| 2024-05-30|
|NOAA-PMEL-OME Stoeck Phytoplankton 18S V4 PCR Protocol | <https://doi.org/10.5281/zenodo.11398119>|v1.0| 2024-05-30|
|NOAA-PMEL-OME AmaralZettler Phytoplankton 18S V9 PCR Protocol | <https://doi.org/10.5281/zenodo.11398105>|v1.0| 2024-05-30|
|NOAA-PMEL-OME LF Metazoan COI PCR Protocol | <https://doi.org/10.5281/zenodo.11398095>|v1.0| 2024-05-30|
|NOAA-PMEL-OME Baker Marmam dLoop PCR Protocol | <https://doi.org/10.5281/zenodo.11398093>|v1.0| 2024-05-30|


## RELATED EXTERNAL PROTOCOLS

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Library Sequencing Preparation from "A comparison of biomonitoring methodologies for surf zone fish communities" | <https://doi.org/10.1371/journal.pone.0260903> | Gold, Z. et al. | 2023-06-13 |
| Library Sequencing Preparation from "Anacapa Toolkit: An environmental DNA toolkit for processing multilocus metabarcode datasets" | <https://doi.org/10.1111/2041-210X.13214> | Curd, E.E. et al. | 2019-05-19 |
| 12S rRNA-Gene Metabarcoding Library Prep: Dual-PCR Method| <https://dx.doi.org/10.17504/protocols.io.4r3l2q9k3l1y/v1> | Andreas Novotny | 2024-06-20 |

These external protocols use the same general Illumina Nextera Unique Dual Index Two Step PCR approach as implemented here. Differences include:

- Master mixes used
- Volume on indices added
- Number of cycles run


### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-05-01 | Initial release |


### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinet|
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|dNTP	|deoxynucleotide triphosphate|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies
|MBARI| Monterey Bay Aquarium Research Institute|
|MBON	|Marine Biodiversity Observation Network|
|NOAA|National Oceanic and Atmospheric Administration|
|NTC	|No template control
|OME	|Ocean Molecular Ecology
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE    | Personal protective equipment |
|UW| University of Washington
| UDI | Unique Dual Index |
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

## BACKGROUND

### Summary

This protocol is used by [Jonah Ventures](https://jonahventures.com/) to prepare next-generation amplicon/metabarcoding sequencing libraries from  NOAA PMEL OME PCR1 products. PCR plates are first cleaned using either the Zymo ZR-96 DNA Clean-Up Kit or Exo1/SAP, then barcoded using unique, sample-specific Illumina Nextera Unique Dual Indices (2x 10bp) or 12-nucleotide index sequence, pooled using mag-bind normalization or the SequalPrep Normalization kit (cat#A10510-01), and sequenced on a NovaSeq 6000 using the SP Reagent Kit v1.5 (500 cycles) (cat# 20028402). Importantly, this standard two-step PCR sequencing library preparation methodology allows for the reuse of indices across multiple markers per sample, enabling 4 plates x 96 samples x 5-8 markers = 1,920-3,071 total libraries with far greater than 100K sequence read depth.

This protocol has been used over multiple years and has evolved over time. There are two variations of the PCR amplicon cleanup, and the PCR normal pool is indicated as option A or B in the protocols and Table of Protocol variations for each OME barcode and sequencing run included below.

### Method description and rationale

Advantages to this protocol include ease of use, leveraging commercially available Illumina sequencing kits and indices, as well as the ability to sequence across the tree of life with a multi-marker approach with up to 384 samples x 8 markers simultaneously. This protocol's steps include: _PCR Amplicon Cleanup_, _Barcoding/Indexing PCR_, _PCR Normalization and Pooling_, and _Sequencing_. 
NOAA PMEL OME conducts eDNA sample collection, filtration, extraction, and PCR1 amplification before this protocol (See our NOAA PMEL OME [Methods](https://zenodo.org/communities/noaa_ome)). Plates of PCR1 product are shipped on dry ice to Jonah Ventures in Boulder, CO, USA, where they are processed using this protocol by the sequencing company. PCR1 product is first cleaned to remove excess primers and dNTPs using either option A) an Exo1/SAP cleanup protocol or option B) Zymo ZR-96 DNA Clean-Up Kit (4 x 96 Preps.) (cat#D4018) (Zymo, Irvine, CA). Cleaned PCR1 product is then indexed through a second barcoding PCR step using Illumina Nextera UDI indices. Indexed PCR2 product is then normalized using option A) mag-bind normalization or option B) SequalPrep Normalization Plates (Life Technologies, Carlsbad, CA) and then pooled by even volume (and concentration) into a final pooled library. The library is then sequenced on an Illumina NovaSeq 6000 at the Texas A&M Agrilife Genomics and Bioinformatics Sequencing Core using the SP Reagent Kit v1.5 (500 cycles). The sequencing core demultiplexes raw sequence data. And downstream bioinformatics is conducted via [REVAMP](https://github.com/McAllister-NOAA/REVAMP).

This protocol is less detailed than our typical protocols, as we do not conduct this protocol ourselves. However, we capture the necessary [FAIRe](https://fair-edna.github.io/) relevant information.

### Spatial coverage and environment(s) of relevance

This protocol can be used for library preparation of any marker gene region of any eDNA or bulk biological sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used such as wearing PPE to avoid skin or eye contact.

### Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time needed to execute the procedure

This protocol takes about 4-5 hours to execute per plate. There is a safe-stopping point after the PCR Amplicon Cleanup, Indexing PCR, Normalization, and Pooling steps. Across all stopping points, the plate can be stored for up to a week at 4°C, with storage at -20˚C for up to 6 months.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| Vortex | Vortex Genie | Scientific Industries | 1 | Can be substituted with generic |
| PCR Plate Centrifuge | Microplate Centrifuge | Generic Brand | 1 | Can be substituted with generic |
| Mag Stand | 96-Well Magnetic Separator | Generic Brand | 1 | Can be substituted with generic |
| 0.5-10 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 100-1000 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 uL 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Serological Pipette | Eppendorf Easypet 3 Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| **Consumable equipment** |
| 96-well PCR plate | Armadillo PCR Plate, 96-well, clear, clear wells | ThermoFisher | 1 | Can be substituted with generic |
| Aluminum Foil Sealing Tape | AlumaSeal II Sealing Foils for PCR and Cold Storage | VWR | 7 | Can be substituted with generic | 
| 8-Strip Tubes | 0.2 mL 8-Strip PCR Tubes | Generic Brand | 5 | tubes without caps attached are better |
| Microcentrifuge Tubes | 2.0 mL Microcentrifuge Tube | Generic Brand | 8 | Can be substituted with generic|
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be substituted with generic - must be sterile and filtered |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be substituted with generic - must be sterile and filtered |
| 25 mL Trough | Reagent Reservoirs - 25 mL Disposable | ThermoFisher Scientific | 1 | (box)  Can be substituted with generic |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| **Chemicals** |
| 80% Ethanol | Molecular biology grade ethanol |
| Exo1/SAP | ExoSAP-IT PCR Product Cleanup Reagent | ThermoFisher Scientific | 1 | (mL vial) is 500 reactions |
| ZR-96 DNA Clean-Up Kit | Zymo ZR-96 DNA Clean-Up Kit | Zymo Research | 4 | 96 preps Cat_No:D4018 |
| Nuclease-free water | Nuclease-Free Water (not DEPC-Treated) | ThermoFisher Scientific | 1 | (mL vial) |
| Illumina Unique Dual Indexes Sets A, B, C, D | Illumina Unique Dual Indexes| Illumina | 1 | Illumina® DNA/RNA UD Indexes Set A, Tagmentation (96 Indexes, 96 Samples) 20091654; Illumina DNA/RNA UD Indexes Set B, Tagmentation (96 Indexes, 96 Samples) 20091656; Illumina® DNA/RNA UD Indexes Set C, Tagmentation (96 Indexes, 96 Samples) 20091658; Illumina® DNA/RNA UD Indexes Set D, Tagmentation (96 Indexes, 96 Samples) 20091660 |
| Promega Master mix | Premixed 2X solution of Taq DNA Polymerase, dNTP,s and Reaction Buffer | Promega | 1 | (kit) Master Mix includes Taq DNA polymerase, dNTPs, MgCl2, and reaction buffer |
| Sera-Mag™ Carboxylate-Modified Magnetic Beads & SpeedBeads | magnetic carboxylate modified particles | Cytvia | 1 | (10 mL) Cat_No:45152105050250 |
| SequalPrep Normalization kit | SequalPrep Normalization kit | Applied Biosystems | 10 | 96 samples Cat_No:A10510-01 |
| NovaSeq 6000 SP Reagent Kit v1.5 (500 cycles) | Includes one SP flow cell, one buffer cartridge, one cluster cartridge, and one sequencing cartridge to support a 500-cycle run on the NovaSeq 6000 System. | Illumina | 1 | (flow cell) Cat_No:20028402 |
| PhiX Control v3 | Kitted DNA control for the Illumina sequencing platform. Compatible with Single and Paired End reads up to 150 base pairs. | Illumina | 1 | (tube) (10ul of 10nM template solution) |
| 1 N NaOH, molecular biology grade | NaOH needed for denaturing DNA | General lab supplier | 1 | (mL) |
| 10 mM Tris-HCl, pH 8.5 with 0.1% Tween 20 | Buffered Tween needed for denaturing DNA | General lab supplier | 1 | (mL) |

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Sterilize workspaces and durable equipment, including pipettes within the BSC, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
2. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. 
3. Run the UV light in the BSC for 30 minutes before starting work.
4. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). Recommended labeling scheme includes plate name, primer, date of PCR, and personnel initials.

#### PCR1 Cleanup 

##### Option A)

PCR1 products were first cleaned by incubating amplicons with Exo1/SAP following the manufacturer's instructions:
1. Remove ExoSAP-IT™ reagent from the –20°C freezer and keep on ice throughout this procedure.
2. Mix 5 μL of a post-PCR reaction product with 2 μL of ExoSAPIT™ reagent for a combined 7 μL reaction volume.
When treating PCR1 product volumes greater than 5 μL, simply increase the amount of ExoSAP-IT™ reagent proportionally.
3. Incubate at 37°C for 30 minutes to degrade remaining primers and nucleotides.
4. Incubate at 95°C for 5 minutes to inactivate ExoSAP-IT™ reagent.
5. Product is stored at -20C.

##### Option B)

PCR1 products were first cleaned by incubating amplicons with Zymo ZR-96 DNA Clean-Up Kit following the manufacturer's instructions:
1. Add 96 ml 100% ethanol (104 ml 95% ethanol) to the 24 ml DNA Wash Buffer concentrate. Add 192 ml 100% ethanol (208 ml 95% ethanol) to the 48 ml DNA Wash Buffer concentrate.
2. In a 1.5 ml microcentrifuge tube, add 25 μL volumes of DNA Binding Buffer to each 5 μL volume of PCR product. Mix briefly by vortexing.
3. Transfer sample mixtures to the wells of a Silicon-A™ Plate mounted onto a Collection Plate.
4. Centrifuge at ≥ 3,000 x g (5,000 x g max.) for 5 minutes until sample mixtures have been completely filtered. Discard the flow-through.
5. Add 300 µl DNA Wash Buffer to each well of the Silicon-A™ Plate. Centrifuge at ≥ 3,000 x g for 5 minutes. Repeat wash step.
6. Add 30-40 µl water directly to the column matrix in each well. Transfer the Silicon-A™ Plate onto an Elution Plate and centrifuge at ≥ 3,000 x g for 3 minutes to elute the DNA.
7. Product is stored at -20C.

##### Quality control
No quality control is conducted.

#### Barcoding/Indexing PCR

1. The indexing PCR (PCR2) included Promega Master mix, 0.5 µM of each Illumina Nextera UDI primer, and 2 µl of template DNA (cleaned amplicon from the first PCR reaction) for a total volume of 25 µL
2.  Thermocycling conditions consisted of an initial denaturation of 95 °C for 3 minutes, followed by 8 cycles of  95 °C for 30 sec, 55 °C for 30 seconds, and 72 °C for 30 seconds. 

**Primer Sequences Used**: Illumina Nextera UDI primer sequences

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| Illumina-Nextera-UDI-PCR-F Index 1 (i7) Adapters | forward | CAAGCAGAAGACGGCATACGAGAT-[**i7**]-GTCTCGTGGGCTCGG |
| Illumina-Nextera-UDI-PCR-R Index 2 (i5) Adapters| reverse | AATGATACGGCGACCACCGAGATCTACAC-[**i5**]-TCGTCGGCAGCGTC|

**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |----- |
| Promega Master mix |1300| 12.5 |100% |50% |
| Forward Primer |104| 1 |10 μM |0.5 μM |
| Reverse Primer |104| 1 |10 μM | 0.5 μM |
| Nuclease-Free Water |884|8.5 | N/A|N/A |
| Template DNA|N/A| 2 | 100%|8% |
| **Total**|**2392**| **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multiplied by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|3min|	1X|
|**Normal Cycling**||||
|Denaturation|	95°C|	30s|	8X|
|Annealing|	55°C|	30s	|8X|
|Extension 	|72°C	|30s	|8X|
|Hold	|4°C	|∞	|1X|

**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located, and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing. This step is post-PCR and thus should occur in the post-PCR spaces.*

1. Set out Illumina Nextera UDI primers and samples to thaw.
2. Vortex and spin down thawed samples, primers, and nuclease-free water. Then tap/flick Promega Master Mix rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make the final master mix, as denoted above in the reagent mixture table.
4. Set out the template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well
8. Seal the PCR plate with foil.
9. Spin down the plate, and then transport in cooler blocks before placing in the thermocycler.
10.  Run thermocycler protocol.

##### Quality control
No quality control is conducted.

#### PCR Normalization and Pooling 

##### PCR Normalization

Option A)

1. A 15µl aliquot of PCR amplicon was purified and normalized using Cytiva SpeedBead magnetic carboxylate modified particles (#45152105050250).

2. Samples were then pooled together by adding 5µl of each normalized sample to the pool.

Option B) 

1. A 15µl aliquot of PCR amplicon was purified and normalized using SequalPrep Normalization kit (cat#A10510-01).

2. Samples were then pooled together by adding 5µl of each normalized sample to the pool.

#### Sequencing

1. Sample library pools were sent for sequencing on an Illumina NovaSeq 6000 (San Diego, CA) at the Texas A&M Agrilife Genomics and Bioinformatics Sequencing Core facility using the SP Reagent Kit v1.5 (500 cycles) (cat# 20028402).

##### Quality Control
Necessary quality control measures were performed at the sequencing center before sequencing.

### Basic troubleshooting guide

- Use a unique index for each sample. Multiple different markers (e.g. MiFish Teleost 12S, 16S Universal Parada, Leray CO1) from different PCRs can be pooled together for sequencing. Similar markers (e.g. MiFish Elasmobranch 12S and Teleost 12S) will be difficult to disentangle bioinformatically.

### Table of Protocol variations for each OME barcode and sequencing run.

| Sequencing Run | Barcode | PCR Amplicon Cleanup | PCR Normal Pool |
| ----- | ----- | ----- | ----- |
|20240328 JV236 Run1|	16Sv4	||	1X






## REFERENCES
1. Curd, E. E., Gold, Z., Kandlikar, G. S., Gomer, J., Ogden, M., O'Connell, T., ... & Meyer, R. S. (2019). Anacapa Toolkit: An environmental DNA toolkit for processing multilocus metabarcode datasets. Methods in Ecology and Evolution, 10(9), 1469-1475.
2. Gold, Z., Koch, M. Q., Schooler, N. K., Emery, K. A., Dugan, J. E., Miller, R. J., ... & Barber, P. H. (2023). A comparison of biomonitoring methodologies for surf zone fish communities. PLoS One, 18(6), e0260903.

## APPENDIX A: DATASHEETS
See [PCR Protocol Sheet](https://github.com/marinednadude/NOAA-PMEL-OME-MiFish-mod-Universal-Teleost-12S-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME%20MiFish%20mod%20Universal%20Teleost%2012S%20PCR%20Protocol%20Sheet.xlsx)
