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

## DNAscope model files for small variant calling (SNVs and indels)
#### PacBio
* [PacBio HiFi whole genome] - Includes model files and a pipeline script.

## LongReadSV model files for structural variant calling
#### PacBio
* [Pacbio HiFi whole genome SV]

#### Oxford Nanopore
* [ONT whole genome SV]

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

[Illumina whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeIlluminaWGS2.0.bundle
[Illumina whole exome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeIlluminaWES2.0.bundle

[MGI whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeMGIWGS2.0.bundle
[MGI whole exome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeMGIWES2.0.bundle

[Element Biosciences whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeElementBioWGS2.0.bundle

[Ultima Genomics whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeUltimaWGS2.0.bundle

[PacBio HiFi whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeHiFiBeta0.5.pipeline.tar.gz

[Pacbio HiFi whole genome SV]: https://s3.amazonaws.com/sentieon-release/other/SentieonLongReadSVHiFiBeta0.1.model

[ONT whole genome SV]: https://s3.amazonaws.com/sentieon-release/other/SentieonLongReadSVONTBeta0.1.model

[Sentieon's appnote on DNAscope for short-reads]: https://support.sentieon.com/appnotes/dnascope_ml/
[Sentieon's appnote on DNAscope LongRead]: https://support.sentieon.com/appnotes/dnascope_hifi/
[Sentieon's appnote on LongReadSV]: https://support.sentieon.com/appnotes/longread_sv/
[DNAscope: High accuracy small variant calling using machine learning]: https://www.biorxiv.org/content/10.1101/2022.05.20.492556v1
[Sentieon DNAscope LongRead – A highly Accurate, Fast, and Efficient Pipeline for Germline Variant Calling from PacBio HiFi reads]: https://www.biorxiv.org/content/10.1101/2022.06.01.494452v1
[Advanced Whole Genome Sequencing Using an Entirely PCR-free Massively Parallel Sequencing Workflow]: https://www.biorxiv.org/content/10.1101/2019.12.20.885517v2
[Sequencing by avidity enables high accuracy with low reagent consumption]: https://www.biorxiv.org/content/10.1101/2022.11.03.514117v1
