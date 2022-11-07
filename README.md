# Update-to-date Sentieon models

Sentieon DNAscope and LongReadSV support variant calling with multiple short and long-read sequencing platforms. For each of these platforms, Sentieon provides model files that can be used to improve variant calling accuracy by accounting for platform-specific bias in the sequencing data. 

In this README, we provide links to the most recent versions of the DNAscope and LongReadSV model files for each platform. This information can also be accessed programmatically from the [sentieon_models.yaml](/sentieon_models.yaml) file in this repository.

DNAscope and LongReadSV are available as part of the Sentieon software package and the model files listed below require a valid license for use. Please contact info@sentieon.com for access to the Sentieon software and an evaluation license.

## DNAscope model files for small variant calling (SNVs and indels)
#### Illumina
* [Illumina whole genome]
* [Illumina whole exome]

#### PacBio
* [PacBio HiFi whole genome] - Includes model files and a pipeline script.

#### MGI and Complete Genomics
* MGI whole genome

#### Element Biosciences
* [Element Biosciences whole genome]

#### Ultima Genomics
* [Ultima Genomics whole genome]

## LongReadSV model files for structural variant calling
#### PacBio
* [Pacbio HiFi whole genome SV]

#### Oxford Nanopore
* [ONT whole genome SV]

## References
**[Sentieon's appnote on DNAscope for short-reads]** - A document with detailed usage information for the Sentieon short-read pipeline.  
**[Sentieon's appnote on DNAscope LongRead]** - A document with detailed usage information for the Sentieon long-read piepline.  
**[Sentieon's appnote on LongReadSV]** - A document with detailed usage information for the Sentieon LongReadSV tool.  
**[DNAscope: High accuracy small variant calling using machine learning]** - A preprint describing DNAscope's methodology.  
**[Sentieon DNAscope LongRead – A highly Accurate, Fast, and Efficient Pipeline for Germline Variant Calling from PacBio HiFi reads]** - A preprint describng the DNAscope pipeine for calling variants from PacBio HiFi data.  
**[Advanced Whole Genome Sequencing Using an Entirely PCR-free Massively Parallel Sequencing Workflow]** - A preprint describing the adaptation of DNAscope for seqeuncing data produced by seqeuncing platforms from MGI/Complete Genomics.

[Illumina whole genome]: https://s3.amazonaws.com/sentieon-release/other/SentieonDNAscopeModel1.1.model
[Illumina whole exome]: https://s3.amazonaws.com/sentieon-release/other/SentieonDNAscopeModelIlluminaWES0.1.model

[PacBio HiFi whole genome]: https://s3.amazonaws.com/sentieon-release/other/DNAscopeHiFiBeta0.4.pipeline.tar.gz

[Element Biosciences whole genome]: https://s3.amazonaws.com/sentieon-release/other/SentieonDNAscopeModelElementBio0.3.model

[Ultima Genomics whole genome]: https://s3.amazonaws.com/sentieon-release/other/SentieonDNAscopeModelUltima0.4.model

[Pacbio HiFi whole genome SV]: https://s3.amazonaws.com/sentieon-release/other/LongReadSVHiFiBeta0.1.model

[ONT whole genome SV]: https://s3.amazonaws.com/sentieon-release/other/LongReadSVONTBeta0.1.model

[Sentieon's appnote on DNAscope for short-reads]: https://support.sentieon.com/appnotes/dnascope_ml/
[Sentieon's appnote on DNAscope LongRead]: https://support.sentieon.com/appnotes/dnascope_hifi/
[Sentieon's appnote on LongReadSV]: https://support.sentieon.com/appnotes/longread_sv/
[DNAscope: High accuracy small variant calling using machine learning]: https://www.biorxiv.org/content/10.1101/2022.05.20.492556v1
[Sentieon DNAscope LongRead – A highly Accurate, Fast, and Efficient Pipeline for Germline Variant Calling from PacBio HiFi reads]: https://www.biorxiv.org/content/10.1101/2022.06.01.494452v1
[Advanced Whole Genome Sequencing Using an Entirely PCR-free Massively Parallel Sequencing Workflow]: https://www.biorxiv.org/content/10.1101/2019.12.20.885517v2
