# Update-to-date Sentieon models

Sentieon DNAscope and LongReadSV support variant calling with multiple short and long-read sequencing platforms. For each of these platforms, Sentieon provides model files that can be used to improve variant calling accuracy by accounting for platform-specific bias in the sequencing data. 

In this README, we provide links to the most recent versions of the DNAscope and LongReadSV model files for each platform. This information can also be accessed programmatically from the [sentieon_models.yaml](/sentieon_models.yaml) file in this repository.

DNAscope and LongReadSV are available as part of the Sentieon software package and the model files listed below require a valid license for use. Please contact info@sentieon.com for access to the Sentieon software and an evaluation license.

## DNAscope model bundles for alignment and variant calling
#### Illumina
* [Illumina whole genome]
* [Illumina whole exome]

#### MGI and Complete Genomics
* [MGI whole genome]
* [MGI whole exome]

#### Element Biosciences
* [Element Biosciences whole genome]

#### Ultima Genomics
* [Ultima Genomics whole genome]

#### PacBio
* [PacBio HiFi whole genome]

#### Oxford Nanopore
* [ONT whole genome]

#### Salus
* [Salus whole genome]
* [Salus whole exome]

## TNscope model bundles for somatic variant calling
#### Ultima Genomics
* [Ultima Genomics whole genome]

## DNAscope model bundles for hybrid short and long-read variant calling
#### Illumina and PacBio
* [Illumina PacBio whole genome]

#### Illumina and ONT
* [Illumina ONT whole genome]

#### Ultima and ONT
* [Ultima ONT whole genome]

## Model bundle files
Model bundles package multiple models into a single file. Bundles use the [`ar` archive format] and the contents of the bundle file can be listed using the command `ar t <bundle>`.

## References
#### Application Notes
**[Sentieon's appnote on DNAscope for short-reads]** - A document with detailed usage information for the Sentieon short-read pipeline.  
**[Sentieon's appnote on DNAscope LongRead]** - A document with detailed usage information for the Sentieon long-read pipeline.  
**[Sentieon's appnote on LongReadSV]** - A document with detailed usage information for the Sentieon LongReadSV tool.  
#### Manuscripts and Preprints
**[DNAscope: High accuracy small variant calling using machine learning]** - A preprint describing DNAscope's methodology, using the DNAscope model for Illumina reads.  
**[Sentieon DNAscope LongRead – A highly Accurate, Fast, and Efficient Pipeline for Germline Variant Calling from PacBio HiFi reads]** - A preprint describing the DNAscope pipeline for calling variants from PacBio HiFi data.  
**[Advanced Whole Genome Sequencing Using an Entirely PCR-free Massively Parallel Sequencing Workflow]** - A preprint describing the adaptation of DNAscope for sequencing data produced by sequencing platforms from MGI/Complete Genomics.  
**[Sequencing by avidity enables high accuracy with low reagent consumption]** - A preprint presenting the Element Biosciences sequencing platform. The preprint uses Sentieon's DNAscope model for Element Biosciences for variant calling.  

[Illumina whole genome]: https://s3.amazonaws.com/sentieon-release/other/SentieonIlluminaWGS2.2.bundle
[Illumina whole exome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeIlluminaWES2.1.bundle

[MGI whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeMGIWGS2.0.bundle
[MGI whole exome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeMGIWES2.0.bundle

[Element Biosciences whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeElementBioWGS2.0.bundle

[Ultima Genomics whole genome]: https://s3.amazonaws.com/sentieon-release/other/SentieonUltima1.0.bundle

[PacBio HiFi whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopePacBio2.1.bundle

[ONT whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeONT2.1.bundle

[Salus whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeSalusWGS1.0.bundle
[Salus whole exome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeSalusWES1.0.bundle

[Illumina PacBio whole genome]: https://s3.amazonaws.com/sentieon-release/other/HybridIlluminaPacBio1.1.bundle
[Illumina ONT whole genome]: https://s3.amazonaws.com/sentieon-release/other/HybridIlluminaONT1.1.bundle
[Ultima ONT whole genome]: https://s3.amazonaws.com/sentieon-release/other/HybridUltimaONT1.0.model.bundle


[`ar` archive format]: https://en.wikipedia.org/wiki/Ar_(Unix)

[Sentieon's appnote on DNAscope for short-reads]: https://support.sentieon.com/appnotes/dnascope_ml/
[Sentieon's appnote on DNAscope LongRead]: https://support.sentieon.com/appnotes/dnascope_lr/
[Sentieon's appnote on LongReadSV]: https://support.sentieon.com/appnotes/longread_sv/
[DNAscope: High accuracy small variant calling using machine learning]: https://www.biorxiv.org/content/10.1101/2022.05.20.492556v1
[Sentieon DNAscope LongRead – A highly Accurate, Fast, and Efficient Pipeline for Germline Variant Calling from PacBio HiFi reads]: https://www.biorxiv.org/content/10.1101/2022.06.01.494452v1
[Advanced Whole Genome Sequencing Using an Entirely PCR-free Massively Parallel Sequencing Workflow]: https://www.biorxiv.org/content/10.1101/2019.12.20.885517v2
[Sequencing by avidity enables high accuracy with low reagent consumption]: https://www.biorxiv.org/content/10.1101/2022.11.03.514117v1
