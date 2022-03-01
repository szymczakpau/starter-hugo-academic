---
title: AMP Frequently Asked Questions
date: 2022-03-01T17:38:19.010Z
---
It was meant to be read in order, so if you are confused about something, you should probably go back to the beginning. 

## What are antimicrobial peptides?

### Peptides

A peptide is a short chain of **amino acids**. 
There are 20 natural amino acids, which are building blocks for peptides. They are connected together by peptide bonds into amino acid chain. They are most commonly represented as one letter, less frequently as three letters:
	

![](https://github.com/szymczakpau/starter-hugo-academic/blob/master/content/post/AMP%20Frequently%20Asked%20Questions%20/aminoacids.png?raw=true)

Using this code, we can represent a peptide like so:

**SHCMELK**

Which corresponds to this chemical structure:

![](https://github.com/szymczakpau/starter-hugo-academic/blob/master/content/post/AMP%20Frequently%20Asked%20Questions%20/peptideexample.png?raw=true)

[Source](https://employees.csbsju.edu/cschaller/Principles%20Chem/imf/SPbiomolecule.htm) 

**What is the difference between a peptide and a protein?** Proteins are composed of polypeptides; they are large and heavy. They can be broken down into smaller chunks. 
Peptides are usually short, starting from two amino acids up to 50-100 amino acids. The boundary between a peptide and a protein is arbitrary. 
One could say that every protein is a peptide, but not every protein is a peptide, but this can be confusing. 

### Antimicrobial

Not every peptide is antimicrobial. To be classified as such, a peptide must show inhibitory activity towards pathogens such as:

* bacteria - antibacterial
* viruses - antiviral
* fungi - antifungal 
* cancer -anticancer
* parasites - antiparasitic 

They can be considered a class of antibiotics, but they have a different mode of action from most commercially available drugs such as ampicylin. We will focus mostly on the bacteria. 

## How did we find out about AMPs?

AMPs were discovered almost a century ago. They were first isolated from a soil *Bacillus* strain and proved to protect mice from pneumococci infection. In following years, they were found in various plants and animals. An especially rich source of AMPs is frog skin. By producing AMPs towards the epithelium, a frog can remain shielded even in the wet surroundings usually favorable to various microbes. 

![](https://i.imgflip.com/66w25w.jpg)

## Where do AMPs come from?

AMPs are produced by various cells, some at a constant rate, some are induced. They are part of innate immune system, produced as a defense mechanism against pathogenic microbes.
While they can be isolated from a natural source, currently the majority of AMPs are synthetic. They can be discovered via rational design or by computational methods.

### Do humans have AMPs?

Yes. They were identified from a variety of tissues and epithelial surfaces, including skin, eyes, ears, mouths, gut, immune, nervous and urinary systems [Wang et al. 2014](https://pubmed.ncbi.nlm.nih.gov/24828484/). 
Most known example are defensins, in particular [Beta-defensin 14](https://dbaasp.org/peptide-card?id=53). 

What is curious, even bacteria can produce AMPs. These are called **bacteriocins**. These are toxic peptides produced by bacteria to inhibit the growth of similar or closely related bacterial strain. 

![](https://i.imgflip.com/66wd95.jpg)

## How do AMP work?

Antimicrobial peptides tend to share a set of common characteristics:

* they are positively charged (fancy biology term for this is ***cationic***)
* they are **amphiphatic**, which means they are hydrophilic (they are soluble in water) and hydrophobic (they can interact with lipid membranes) at the same time.

Both those physicochemical properties are a direct result of the amino acid composition which influences charge, hydrophobicity and the structure. 

Every bacterial cell is enveloped with a lipid membrane. It is a semi-permeable structure that allows the passage of nutrients and excreted products, and also protects the cell from the outside. As a rule, it is negatively charged. 

We have a positively-charged peptide and negatively-charged bacterial membrane. The attraction between charges initiates contact between the peptide and the bacterial cell. The amphiphatic nature of the AMPs allows them to interact with the lipid membrane, causing cell lysis, or to put simply, killing the bacterial cell.  

![](https://i.imgflip.com/67102g.jpg)
[Nagajaran et al. 2018](https://pubmed.ncbi.nlm.nih.gov/29259134/)

The modes of action can differ between peptides and between bacterial species. The lipid membrane is not the only target, and the physicochemical properties are not always followed. In biology, there are no theorems. 

## Why do we care about AMPs?

Bacteria are slow to develop resistance against them. Traditional antibiotics tend to trigger resistance mechanisms in bacteria, but AMPs remain active after prolonged exposure due to their mode of action. 

![](https://github.com/szymczakpau/starter-hugo-academic/blob/master/content/post/AMP%20Frequently%20Asked%20Questions%20/resistanceassay.png?raw=true)

*When to AMPs (YI12, FK13) are compared with a common antibiotic Imipenem, bacteria are quickly developing resistance towards Impipenem (starting from passage 5). The concentration needed kill bacteria remains stable for both AMPs.* [Das et al. 2021](https://www.nature.com/articles/s41551-021-00689-x) 

AMPs could be considered a **novel class of antibiotics**. 

## Why AMPs are not currently on the market as antibiotics?

The same features that make AMP active against bacteria are making them active against host cells. Toxicity and activity are correlated features.

![](https://i.imgflip.com/67119v.jpg)

Cells such as human erythrocytes are neutral in terms of charge, and some antimicrobial peptides are capable of selectively target bacterial cells without destroying host (human) cells. **Optimizing the selectivity of AMPs is the most important target is AMP design.** 

## How do we quantify antimicrobial activity and toxicity?

To quantify activity we use **Minimal Inhibitory Concentration (MIC)**. It is measured experimentally against specific bacterial strains (e.g. *E. coli* or *S. aureus*), as the lowest concentration of a peptide which prevents visible growth of the bacteria. The most active peptides have very low values of MIC, which means that they are active even in extremely low concentrations, which is good, because it means we can administer lower dosage. 

To quantify toxicity, we use **Hemolytic Concentration 50% (HC50).** It is the concentration of peptides that kills 50% erythrocytes. 

The ratio of HC50 to MIC is called **Selectivity Index (SI).** Higher HC50 values combined with low MIC values mean that the peptide is active against bacteria in low concentrations, remaining harmless to host cells. 

## Where can I find info on AMPs?

AMPs are collected in the databases by the AMP community. Here are some of worth recommending: 

* [Database of Antimicrobial Activity and Structure of Peptides (DBAASP)](https://dbaasp.org/)
* [Data repository of antimicrobial peptides (DRAMP)](http://dramp.cpu-bioinfor.org/)
* [Collection of Anti-Microbial Peptides (CAMP)](http://www.camp3.bicnirrh.res.in/)

## Why not just leave this problem to biologists?

Novel AMPs are usually discovered by trial and error process of substituting and/or introducing certain amino-acids into already known AMPs. These small changes can substantially affect antimicrobial activity. In silico design allows for excellent activity and low toxicity.

|                         | Pexiganan                                                                     | Flexampin                                |
| ----------------------- | ----------------------------------------------------------------------------- | ---------------------------------------- |
| Sequence                | GIGKFLKKAKKFGKAFVKILKK                                                        | GIKKWVKGVAKGVAKDLAKKIL                   |
| Description             | Topical cream for diabetic foot ulcers  (failed in Phase III clinical trials) | Designed in silico with expert knowledge |
| MIC against E. coli(µM) | 1.60                                                                          | 0.30                                     |
| HC50 (µM)               | 45                                                                            | \> 200                                   |
| Selectivity             | 28                                                                            | 670                                      |

However, the combinatorial space of peptides is huge. Moreover, not every sequence is valid, some peptides cannot be synthesized and few manifest antimicrobial activity. The high cost of wet-lab experiments results in a limited number of experimentally validated peptides. 

We need efficient and accurate *in silico* approaches to novel AMP generation.