Source: <https://freewechat.com/a/MzAxMjMyMDk0Ng==/2650112053/1/1580318101>,
archived at <https://archive.ph/Zretg>

Text translated using [deepL](https://www.deepl.com);  
images translated with Google Lens.

---

*This content has been removed by the publisher This content was recovered by Free WeChat.  
The article was detected as deleted on Jan 31, 9:31 PM.*

# Documenting the first experience of discovering a novel coronavirus

*2020-01-30 Original Winjor 小山狗 Little Mountain Dog*

On December 26, 2019, I just started work. As usual, I will go through the mNGS pathogenic microbial automated readings for the day, and if there are no problems, I will start my R&D work for the day.

Unexpectedly, I found that one sample reported a sensitive pathogen, SARS coronavirus, with dozens of sequences, and there was only one meaningful pathogen in this sample, which would have been a fairly reliable result if it was an ordinary virus. The heart is tight, rushed to the background to view the detailed analysis data, found that the similarity is not very high, only about 94.5% (this is related to the threshold of card similarity, equivalent to only filter down the sequence with a high degree of similarity). Several possibilities came to mind: 1. there are certain differences in the genomes of different strains of SARS; 2. RNA viruses are prone to mutation, and 17 years after the SRAS event, the variation is relatively large; 3. incorrect comparison of closely related species, etc. In order to confirm the reliability of the results, a detailed analysis was started.

The good thing is that I have already encountered this kind of sensitive pathogen confirmation analysis work several times before, and the leader has also discussed with me several times whether we can do a new pathogen automatic mining analysis process, and I have always kept this in mind, and I have made a preliminary version of it when doing other projects with higher weight and priority, and this sample can just be used. I gave it a name, and it has an additional suffix: "Exploratory Version", which includes almost all sequenced viral genomes, compared to the daily production analysis process.

The results of the Exploratory Edition analysis suggest that this pathogen is most similar to Bat SARS like coronavirus, with an overall similarity of about 87%, while the similarity to SARS is about 81%. The number of sequences on the comparison rose from a few dozen to more than 500, and in addition 5 contigs were also assembled, adding up to more than 1200 bp, at which point it was basically confirmed to be a coronavirus and could be analyzed in detail for coronaviruses. During the analysis, we also started a small internal confidential discussion with the head and leader of the interpretation.

![screenshot1](pics/littledog_1_translated.png)

*December 26, 2019 09:28 am  
SARS are out  
Omg, which sample  
it's no joke  
It's the same level as the plague  
Which sample?*

Further analysis, whether we take the original sequence to NCBI nt library blastn or take the assembled sequence to blastn, the result is most similar to Bat SARS like coronavirus, but the overall similarity is also only about 87%, and the similarity for nr library protein blastx comparison is also similar, so we reserve doubt on the result.

![screenshot2](pics/littledog_2_translated.png)

*Is bat coronavirus as infectious as SARS?  
You handle this sample alone  
Well, I'm analyzing  
SARS itself came from bats  
And civet cats  
December 26, 2019 at 10:24 am  
Bat_SARS_like_coronavirus  
The final identification is this  
December 26, 2019 at 10:25 am  
Taxonomically a subtype of SARS*

The classification information of viruses has been confusing, and the classification rules are not uniform, some are based on typing genes (such as influenza A), others do not have clear typing genes, and are classified by other methods. We have not researched the classification of Bat SARS like and SARS before, but in NCBI Taxonomy, Bat SARS like is classified under SARS. Based on the genomic similarity, I subconsciously thought that since Bat SARS like was a subordinate classification of SARS, the unknown virus detected was at least a parallel species to Bat SARS like, i.e., a novel Bat SARS like (later, I read the literature). SARS and Bat SARS like are classified by several non-structural proteins).

![screenshot3](pics/littledog_3.jpg)

Several thousand coronavirus genomes were further carpet-analyzed and evaluated in terms of similarity, coverage, and uniform genome distribution, and finally the two most similar strains were identified, bat-SL-CoVZC45 and bat-SL-CoVZXC21 (the same two that were analyzed in many articles after the genome sequence was published on January 9).

(Figure posted to the group only this afternoon)

![screenshot4](pics/littledog_4_translated.png)

---
December 26, 2019 at 14:42 pm
Now the information analysis can confirm that it
is SARS virus, but it is not sure whether it
is a new subtype.
December 26, 2019 at 15:01 pm
933.1 at SARS coronavirus isolate bat SL COVZC45 complete genome Caver
9341 Bat SAR-ke coronavirus isolate bat-SL-COVZXC21 complete genome Cove
0621801 SARS coronavirus Urbani isolate icSARS-MA com by Co
From the sequence number and coverage
map, it is the best fit for Bat_SARS_like_coronavirus
---
