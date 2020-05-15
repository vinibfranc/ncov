---
title: Genomic analysis of COVID-19. Situation report 2020-05-15.
authors:
  - Sidney M. Bell
  - Emma Hodcroft
  - Nicola Müller
  - Cassia Wagner
  - Misja Ilcisin
  - James Hadfield
  - Richard Neher
  - Trevor Bedford
authorLinks:
  - https://twitter.com/sidneymbell
  - https://neherlab.org/emma-hodcroft.html
  - https://bedford.io/team/nicola-mueller/
  - https://bedford.io/team/cassia-wagner/
  - https://bedford.io/team/misja-ilcisin/
  - https://bedford.io/team/james-hadfield/
  - https://neherlab.org/richard-neher.html
  - https://bedford.io/team/trevor-bedford/
affiliations: "Fred Hutch, Seattle, USA; Biozentrum, Basel, Switzerland; CZI, CA, USA"
translators:
translatorLinks:
license: "CC-BY"
licenseLink: "https://creativecommons.org/licenses/by/4.0/"
dataset: "https://nextstrain.org/ncov/global/2020-05-14?d=tree&legend=closed"

abstract: "This weekly report uses publicly shared genomic data to track the spread and evolution of SARS-CoV-2. This week, we focus on how the virus emerged and has changed over the course of the pandemic. We also discuss related concerns raised in the media."
---
<!-- Translators: Only text after : in the above ^ needs to be translated -->
<!-- Comment tags like these do not need to be translated, they are only to help you! -->
<!-- Ensure that links always end in a 'letter' (. counts) If some kind of text doesn't follow them, it breaks the slide. -->
<!-- numbers can be tagged ilke this: 161</tag> - this is just for us to help find them to update! Just leave in the </tag> bit. -->

<!-- This is left-side text -->
# [Executive summary](https://nextstrain.org/ncov/2020-05-14?d=tree,map&p=grid)


<!-- This is right-side text -->
```auspiceMainDisplayMarkdown
# This week: all about viral mutations  

We analyzed 5,193 publicly shared COVID-19 genomes. By comparing these viral genomes to each other, we can characterize how SARS-CoV-2 is evolving and moving around the world. This week, we focus on viral mutations -- where they come from, what they mean, and how they're useful. We cover:
<br><br>
* Where viral mutations come from (they're normal)  
* The rate of mutation in SARS-CoV-2 (very typical)
* How many strains of SARS-CoV-2 are circulating (as far as we know: 1)  
* How geography and epidemiology contribute to perceived differences in viral genotypes (this is tricky)

```


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text 2-->
# [COVID-19 Resources](https://nextstrain.org/ncov/global/2020-05-14?d=tree&p=full&legend=closed)
We've prepared some resources that will make interpreting the data we present in this narrative easier.
#### Nextstrain Resources
* [START HERE: How to read a phylogeny](https://nextstrain.org/narratives/trees-background/).
* [Previous Situation Reports](https://nextstrain.org/ncov-sit-reps/).
* [Background on coronaviruses](https://nextstrain.org/help/coronavirus/human-CoV).
* [Common misconceptions](https://nextstrain.org/narratives/ncov/sit-rep/2020-03-13?n=11).

#### External Resources
* [Ask a Scientist & FAQs](https://covid19.fas.org/l/en).
* [WHO Situation Reports](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports).
* [CDC Resources](https://www.cdc.gov/coronavirus/2019-ncov/index.html).
* [The NYTimes COVID-19 coverage](https://www.nytimes.com/news-event/coronavirus).
<!-- There is no right-side text -->


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text -->
# [Situation Report Hiatus](https://nextstrain.org/ncov/global/2020-05-14?c=country&r=country&d=map&p=grid&legend=closed)

Early in the pandemic, it was unclear how SARS-CoV-2 was moving between countries, where it was circulating locally, and how localized outbreaks were related.
Over the last four months, we've tackled these questions and more in our weekly Situation Reports. At this stage of the pandemic, it's clear that these broad-strokes patterns are largely consistent across regions and countries:  
<br><br>
- Outbreaks across even distant parts of the world are deeply intertwined.  
- Through human migration and travel, the virus has been introduced to most communities multiple times.  
- Once these "sparks" land in a new community, many fizzle out without causing widespread transmission. Subject to local conditions and a bit of chance, some of these sparks grow into local outbreaks.  
- Eventually, these local outbreaks send of sparks of their own, spreading to new locations.  
<br><br>
Unsurprisingly, we see this pattern in countries experiencing their first wave of infections. More alarmingly, we also see this pattern after reintroduction to  countries where the initial peak passed months beforehand.
Ultimately, this pattern is only broken when a country is able to effectively test, trace, and isolate cases immediately.
<br><br>
This means that outbreaks across the world are deeply intertwined, and the battle against COVID-19 will always be global -- we can't conquer the virus anywhere without addressing it everywhere.
<br><br>
But, at this stage of the pandemic, genomic epidemiology is most urgently needed within hyperlocal communities through local public health offices.
<br><br>
As such, this will be our last weekly Situation Report for awhile as we shift our focus to supporting local public health officials.
<br><br>
We will, of course, continue daily updates to the global & regional builds as new sequences are posted to GISAID.
When the big-picture data says something new, we'll also issue additional Situation Reports.
All of these updates will be posted to the [Nextstrain twitter account](https://twitter.com/nextstrain) (as always).  
<br><br>
You can also find [all of our previous Situation Reports here](https://nextstrain.org/ncov-sit-reps/).
<!-- There is NO right-side text -->


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [Viral mutations are normal and help us trace outbreaks](https://nextstrain.org/ncov/global/2020-05-14?c=gt-ORF3a_57&d=tree,entropy&f_division=New%20York&m=div&p=full)

[SARS-CoV-2 is a coronavirus](https://nextstrain.org/help/coronavirus/human-CoV). Like other coronaviruses, SARS-CoV-2 has a genome encoded in RNA (rather than DNA).

Viruses infect cells because they need to borrow cellular machinery to replicate. For RNA viruses, this process is quite error-prone, as most RNA polymerases (the cellular machines that make copies of RNA) aren't able to proofread and correct their work. This leads to frequent mutations in the viral genome; these are normal and expected.
<br><br>
Importantly, the vast majority of these mutations either "break" the virus such that it can't transmit and/or replicate anymore, or don't change the virus at all because of [redundant encoding](https://en.wikipedia.org/wiki/Synonymous_substitution).
Rarely, a mutation can help the virus replicate and/or transmit better, but nearly all of these changes still have only a tiny effect.
<br><br>
Usefully, though, these mutations can be used as "bread crumbs" to trace the history of a given sample. Just as the people in your family share unique combinations of genetic characteristics, closely related viral samples share unique combinations of genetic mutations.
<br><br>
For example, here we show the viral "family tree" with each sample colored by which amino acid is present at a specific location in the viral genome (ORF1a, site 57). Highlighting samples from New York, we see that most of the cases from New York and Europe have the amino acid Histidine ("H") rather than Glutamine ("Q") at this position. This, in combination with all the other sites in the genome, tells us that these cases are all closely related to each other.
<br><br>
For a more in-depth explanation of these concepts, we recommend [this visual explanation](https://www.nytimes.com/interactive/2020/04/30/science/coronavirus-mutations.html) by Jonathan Corum and Carl Zimmer.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [The mutation rate of SARS-CoV-2 is quite typical (and not at all alarming)](https://nextstrain.org/ncov/global/2020-05-14?c=num_date&d=tree,entropy&l=clock&p=full)  

Because mutations are biologically inevitable, they tend to accumulate at a steady rate over time.

Here, the x axis shows the date that each sample was collected. The y axis shows the *total number* of mutations away from the root of the tree. Each sample is colored by which region of the world it was collected in.

While there are certainly some outliers, on average, we see changes accumulate at a rate of ~24 substitutions per year. This means that if a single viral lineage were transmitting from one person to the next for a full year, we'd expect it to accumulate roughly 24 substitutions by the end of the year. Importantly, this corresponds to only (24/30,000)\*100% = ~0.08% of the viral genome changing each year.

For context, SARS (also a coronavirus) accumulates XX substitutions per year (changing XX% of its genome), while influenza accumulates XX substitutions per year (changing XX% of its genome).


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [As far as we know, there is only 1 "strain" of SARS-CoV-2](https://nextstrain.org/ncov/global/2020-05-14?branchLabel=clade&c=clade_membership&d=tree&p=full)  

There have been many reports about multiple "strains" of SARS-CoV-2.
First, a clarification: when virologists use the word "strain," it often just refers to a handy label so we can all refer to the same group of samples (e.g., our clade labels shown here). This does *not* imply any known functional difference.
<br><br>
Separately, "strain" can be used to refer to viral genotypes that are functionally distinct, either biologically (e.g., pathogenicity/disease severity) and/or epidemiologically (e.g., transmissibility).
Importantly, though, determining whether two genotypes actually *are* functionally distinct requires much more experimental, clinical and epidemiological data than we currently have.
<br><br>
One of the most prominent hypotheses about SARS-CoV-2 strains compares possible "D614" vs "G614" strains. We can use Nextstrain to investigate.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text -->
# [D614G may be related to transmissibility, but could also be explained by geography](https://nextstrain.org/ncov/global/2020-05-14?c=gt-S_614&gmax=25778&gmin=21082&p=full)  

[A recent paper](https://www.biorxiv.org/content/10.1101/2020.04.29.069054v1) suggests that a single mutation, D614G (from amino acid "D" to "G" at site 614), may be responsible for increasing the transmissibility and/or pathogenicity of SARS-CoV-2.
<br><br>
The primary evidence for this hypothesis is based on how relative frequencies of each genotype change over time.
If a given genotype is bad at transmitting, it is expected to decrease in frequency over time (and vice versa).
<br><br>
For this site, we see a number of geographic locations where initially, most viral lineages in circulation had the D allele; later, this balance flips such that most lineages have the G allele.
This *could* be a hallmark of G being slightly "fitter" than D (e.g., if it did indeed have a slightly higher R0 through increased transmissibility).
<br><br>
However, this could also just be a side effect of the natural history of the pandemic.
Early on in the pandemic, most strains exported from China had a D allele. Later, most strains from Italy had a G allele. Recently, we've seen more exportation from Europe than from Asia overall (although there's certainly some sampling bias at play here).
Thus, it could just be that this particular genotype got lucky, and spread so rapidly because it got there first.
<br><br>
There's a fair amount of debate regarding the relative merits of these two hypotheses. It'll be important to carefully tease these apart, but we don't have scientific consensus on this issue yet.


<!-- ############ SLIDE BREAK ############# -->
<!-- This is left-side text 13-->
# [What you can do](https://nextstrain.org/ncov/2020-03-27?c=country&d=map&p=full)
#### ...as an individual
* Practice strict social distancing, especially if you are in a vulnerable group.
* Remember that even if you are not super vulnerable, many people around you are; follow these practices to protect others.
* Wash your hands "like you just chopped a jalapeno and have to change a contact lens."
* Stay home as much as possible -- especially  if you are sick; be prepared with extra supplies in case you need to self-quarantine.
* If you are an employer, encourage your employees to work from home wherever possible.

#### ...as an official
* Make testing free and broadly available.
* Put strong social distancing measures in place.
* Fund and implement extensive contact tracing efforts.
* Financially support those impacted by social distancing measures.


<!-- This is the right-side text -->

```auspiceMainDisplayMarkdown
# Takeaways

####
<br><br>
####
<br><br>



```

<!-- ############ SLIDE BREAK ############# -->






<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text -->
# [Scientific credit](https://nextstrain.org/ncov/2020-05-14?d=map&c=author)

We would like to acknowledge the amazing and timely work done by all scientists involved in this outbreak, and particularly those working in China.
Only through the rapid sharing of genomic data and metadata are analyses such as these possible.

<br>

We also gratefully acknowledge [GISAID](https://gisaid.org) for providing the platform through which these data can be uploaded and shared.

<!-- Do not need to translate institutions names -->
<!-- This is right-side text -->
```auspiceMainDisplayMarkdown

We are grateful for the data gathered by these originating labs:



```


<!-- ############ SLIDE BREAK ############# -->

<!-- This is left-side text -->
# [Detailed scientific credit](https://nextstrain.org/ncov/2020-03-05?d=map&c=author)

These data were shared via [GISAID](https://gisaid.org).
We gratefully acknowledge their contributions.

<br>

To the right we give specific sequences shared by each lab.

<!-- This is right-side text -->
```auspiceMainDisplayMarkdown

The SARS-CoV-2 genomes were generously shared by scientists at these submitting labs:




```