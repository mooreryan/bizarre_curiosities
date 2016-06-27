**[Rapid evolution of the human gut virome](http://www.pnas.org/content/110/30/12450.long)** (2013)

*cool*

- Analyzed viromes of one individual over 2.5 years
- Metagenomic sequencing
- 80% of viral types persisted -- stability
- Examining evolution of members and substitution raties (temparate phage lower than lytic)
- CRISPR

**[Hypervariable loci in the human gut virome](http://www.pnas.org/content/109/10/3962.long)** (2012)

- Genetic variation -> microbial immune evasion and drug resistance
- Looked at DNA viruses in GI tract of 12 humans
- Identified loci with high variation and the genes with which they correspond
- Hypervariation was targeted to certain asparagine codons

**[Gut DNA viromes of Malawian twins discordant for severe acute malnutrition](http://www.pnas.org/content/112/38/11941.long)** (2015)

- Time series viromes from fecal samples of twins looking at differences in severe acute malnutrition (SAM)
- Used Random Forests (some technique)
- Viruses can discriminate discordant from concordant healthy pairs

**[Biogeography of bacteriophages at four hydrothermal vent sites in the Antarctic based on g23 sequence diversity](http://femsle.oxfordjournals.org/content/363/7/fnw043.abstract)** (2016)

- Four hydrothermal vent sites with differing chemical characteristics
- Marker gene g23 (gp23 - major capsid protein T4 like)
- "We found that the sites differ vastly in their bacteriophage diversity, which reflects the differences in the chemical conditions and therefore putatively the differences in microbial hosts living at these sites."
- Also compared vent samples to other non vent samples -> showed differences (got sequences from other studies)

- Methods
    - PCoA (UniFrac) and NMDS (Bray-Curtis) were used
    - 454 and Sanger sequencing

- Sequencing info
    - 84 Sanger clones
    - Primers MZIA1 and MZIA6 (Filee et al. 2005)
    - GenBank acc numbers KT897956 - KT898038, and bioproject PRNJA298523

- Clustering and trimming

    > Sanger sequences were quality checked and trimmed to 200 nt using Geneious v5.4. 454 sequence data was quality checked and filtered (maxee = 0.5) and trimmed with USEARCH (Edgar 2010). Sequences shorter than 200 nt were discarded, longer sequences were trimmed to a length of 200 nt. The 200 nt cutoff was chosen as the best compromise between high-quality sequence data and sequence length. Sanger and 454 fasta files were then combined, clustered (threshold 97%) and an OTU table was created with USEARCH and associated python scripts. This resulted in a total of 1517 sequences that passed quality control and clustered into 342 OTUs.

**[High diversity and potential origins of T4-type bacteriophages on the surface of Arctic glaciers](http://link.springer.com/article/10.1007/s00792-013-0569-x)** (2013)

- Looked at T4-like phage in surface of two glaciers in Svalbard (Norwegian archipelego)
- Marker gene g23 (gp23 - major capsid protein T4 like)
- Most phage in this study formed three novel phylogenetically distinct groups, with the remainder clustering with other marine and soil phage
- They did a transplantation experiment to see if phage from different fjord could infect other bacteria
- Main takeaway -> "the surface of glaciers contain both novel and cosmopolitan phages, some of which may have arrived in the cryosphere from other biomes." -> ie you can see differences based on location

- Sequencing info
    - 43 unique g23 clones
    - GenBank accession numbers: JQ996716–JQ996802

- On the limits of the primers for detecting cyanophage
    - "The PCR primers used in this study have primarily detected cyanophages infecting unicellular cyanobacteria, particularly marine strains (Filée et al. 2005; Deng and Hayes 2008)."
    - "Concurrently, a study on UK freshwater lakes found that most cyanophages isolated from the water column were unable to be amplified by targeting g20 or g23 genes (Deng and Hayes 2008). It is probable therefore that cyanophages infecting filamentous freshwater species have highly novel capsid assembly protein genes, thus the PCR primers selected in this study were unable to anneal to cyanophages DNA from cryoconites."

**[Phylogenetic diversity and assemblage of major capsid genes (g23) of T4-type bacteriophages in paddy field soils during rice growth season in Northeast China](http://www.tandfonline.com/doi/abs/10.1080/00380768.2012.703610)** (2012)

- Marker gene g23 (gp23 - major capsid protein T4 like)
- Five rice paddy field soils in China

- Sequencing info
    - 126 different g23 clones
    - GenBank accession numbers: JQ996716–JQ996802

- Biogeography (see figures) (got sequences from other studies)
    - UniFrac showed g23 clone assemblages from different environments (marine, lake, paddy field soil, upland soil) differed in community composition
    - Even within paddy field soil, the t4-like phage community composition differed (Northeast China vs Japan)
    - Showed pretty strong phylogenetic signal based on geographical location

![/Users/moorer/.emacs.d/markdown_image_files/images_for_Users_moorer_Documents_Lab_Notebook_Annotated_Bibliography_studies.md/Screen_Shot_2016-06-24_at_12.04.46_PM.png](/Users/moorer/.emacs.d/markdown_image_files/images_for_Users_moorer_Documents_Lab_Notebook_Annotated_Bibliography_studies.md/Screen_Shot_2016-06-24_at_12.04.46_PM.png)

![/Users/moorer/.emacs.d/markdown_image_files/images_for_Users_moorer_Documents_Lab_Notebook_Annotated_Bibliography_studies.md/Screen_Shot_2016-06-24_at_12.08.12_PM.png](/Users/moorer/.emacs.d/markdown_image_files/images_for_Users_moorer_Documents_Lab_Notebook_Annotated_Bibliography_studies.md/Screen_Shot_2016-06-24_at_12.08.12_PM.png)

**[Biodiversity and distribution of polar freshwater DNA viruses](http://advances.sciencemag.org/content/1/5/e1400127.abstract)** (2015)

- Apparently this is "the first metagenomic analysis of Arctic freshwater viral DNA communities and comparison with other freshwater environments"
- These viromes had mostly unknown and ssDNA viruses with no known relatives in databases
- Not much genetic overlap with other studied environments
- Arctic and Antarctic DNA viromes differ at "fine-grain genetic level while sharing a similar taxonomic composition"
    - crAss showed differences in location (viromes from similar locations more similar)
- Viromes were partitioned by polar and nonpolar viromes (mainly driven by rel. abund. of small circular ssDNA viruses and unclassifed phage)
- Some viral lineages had a bipolar distribution "suggesting a global dispersal capacity for viruses, and seemingly indicates that viruses do not follow the latitudinal diversity gradient known for macroorganisms"
    - Honestly not sure how they made this conclusion based on the figures in the paper

- Methods
    - *Cool stats:* look at this paper for ideas for stats analyses
    - On the other hand they used crAss and GAAS both of which I think are not great, especially GAAS which I think is terrible
    - Cross tBLASTx searches (like eric's blasters?)

**[Characterization of the Major Capsid Genes (g23) of T4-Type Bacteriophages in the Wetlands of Northeast China](http://link.springer.com/article/10.1007/s00248-012-0158-z)**

- Wetlands and paddy fields
- Marker gene g23 (gp23 - major capsid protein T4 like)
- g23 clones in natural wetlands (whether it was water or soil) were different from those in marine waters, lakes, and upland black soils, but were similar to paddy fields

- Methods
    - UniFrac

- Sequencing info
    - 96 g23 clones from natural wetlands, and 50 clones from paddy field

**[Seasonality and monthly dynamics of marine myovirus communities](http://onlinelibrary.wiley.com/doi/10.1111/j.1462-2920.2012.02744.x/full)** (2012)

- Marker gene g23 (gp23 - major capsid protein T4 like)
- TRFLP for g23
- Three year times series, monthly observations
- About a quarter of OTUs were detected in at least 31 months
- Seasonal variation was seen
- Certain OTUs persist all year
- Discriminant function analysis was used to select taxa that best predict months (might need to try this)
- This paper is intense

**[Phylogenetic Distribution of the Capsid Assembly Protein Gene (g20) of Cyanophages in Paddy Floodwaters in Northeast China](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0088634)** (2014)

- Looked at diversity of cyanophage in paddy fields (in NE China)
- Marker gene g20 (gp20 - viral capsid assembly protein)
- DGGE, 54 clones
- Biogeographical differences could be seen in pcoa (unifrac) analysis between marine water, lake freshwater and paddy fields
- Phylogenetically these clones were distinct from those from Japanese paddy fields

**[Viral infection of bacteria and phytoplankton in the Arctic Ocean as viewed through the lens of fingerprint analysis](http://www.int-res.com/abstracts/ame/v72/n1/p47-61/)** (2014)

- DNA polB (Phycodnaviridae -- infecting phytoplankton) and g23 (gp23 - Myoviridae infecting bacteria)
- Viruses infecting phytoplankton -- the genetic composition varied with changes in productivity and hydrological conditions as well as changes in the potential host community (shown by DGGE fingerprints of 18S rDNA)
- Viruses infecting bacteria -- no changes were seen in response to changes in environmental variables or DGGE fingerprints of either bacteria (16S) or eukaryotic (18S) rDNA

**[Short-term observations of marine bacterial and viral communities: patterns, connections and resilience](http://www.nature.com/ismej/journal/v7/n7/abs/ismej201319a.html)** (2013)

*Cool*

- Sampled once per day for 38 consecutive days, plus seven additional samples over 40 or more days at another location
- Bacterial communities -- ARISA, viral communities TRFLP for g23 (just like the other Furmanh study)

- "Common bacterial and viral taxa were consistently dominant, and relatively few displayed dramatic increases/decreases or ‘boom/bust’ patterns that might be expected from dynamic predator-prey interactions"

- Most associations occured either among bacteria or among viruses
- Some modular associations were seen
- Most association between bacteria and viruses occured with a median time lag of 2 days
- They quantified the rate of bacterial community change using regression of all pairwise bray-curtis similarities between samples *COOL!!!*

- "Our interpretation is that, over the scale of days, individual bacterial and viral OTUs can be dynamic and patterned; resulting in statistical associations regarded as potential ecological interactions."

- "However, over the scale of weeks, average bacterial community variation is slower, suggesting that there is strong community-level ecological resilience, that is, a tendency to converge towards a ‘mean’ microbial community set by longer-term controlling factors."