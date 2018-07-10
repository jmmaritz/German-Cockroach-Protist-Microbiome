# German-Cockroach-Protist-Microbiome
Protists in the guts and feces of German Cockroaches

### DESCRIPTION

This fileset contains QIIME and R commands and outputs used to carry out the 8S rRNA gene analysis in the manuscript:

Kakumanu, M. L., Maritz, J. M., Carlton, J. M., and Schal, C. (2018) [Overlapping Community Composition of Gut and Fecal Microbiomes in Lab-Reared and Field-Collected German Cockroaches][Paper] *Appl Environ Microbiol* 84: 17.

Gut, fecal and whole insect samples from lab-reared and field-collected German Cockroaches were subjected to marker gene sequencing for the 16S rRNA and 18S rRNA genes.

### DATA:

You will need to download the raw Illumina sequence data from the SRA under BioProject [PRJNA415481][Bioproject].

You will also need to download the curated database used in this analysis.
Information on this can be found in my Github repository [Curated-SILVA-Database][github_database] and the the complete database can be downloaded from [Figshare][Database]

Alternatively, I have provided QIIME formatted [OTU files](/Data) from the original analysis for download.

### REQUIREMENTS:

Trimmomatic 0.32, Qiime 1.9.0, ea_utils 1.1.2, python 2, USEARCH 8.0.1, blast 2.2.22

R packages: phyloseq 1.20.0, vegan 2.4-3, ggplot2 2.2.1, extrafont 0.17, gridExtra 2.2.1

[Paper]: http://aem.asm.org/content/early/2018/06/25/AEM.01037-18
[Bioproject]: https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA415481
[github_database]: https://github.com/jmmaritz/Curated-SILVA-Database
[Database]: https://doi.org/10.6084/m9.figshare.3114850.v1

