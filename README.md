# Woods-et-al-2025-J-Economic-Entomology
Data and code to reproduce analyses in Woods et al. 2025. Effect of imidacloprid application timing on twospotted spider mite (Acari: Tetranychidae) on hop. Journal of Economic Entomology 

The data set is from three years of experiments conducted to quantify the impact of foliar-applied imidacloprid effects Tetranychus urticae and its key predators on hop.
These files are provided to enable full reproducibility of the statistical analysis presented in the paper. We make no warranties regarding these programs.
Corresponding author: David H. Gent dave.gent@usda.gov

# Files
Three CSV files are given with the data sets.

Provado.csv
--This contains the data from the leaf-level assessments of arthropods

Shake.csv
--Canopy shake sample data set

Yield.csv
--Yield, hop chemistry, and various quality metrics

Woods et al 2025 Imidacloprid Data and Code.SAS
--This file contains the SAS version 9.4 code (and data) to reproduce the analyses.


# Variable Description
## Leaf level data for Provado.csv

Note that not all of the arthropods observed on leaves were reported in the manuscript.

Year: 2021, 2022, and 2023

Date: MM/DD/YY format

Block: Replicate block indicted with Roman numerals I to VIII for the eight replicate blocks

TRT: Treatment, where 1 = nontreated, 2 = imidacloprid applied in May, and 3 = imidacloprid applied in June

Height: Height in the canopy where leaves were collected, either Lower (<2 m) or Upper (>2 m)

Leaf: Subsampled leaves collected from each height x block x trt

TSSM: Motile Tetranychus urticae

TSSM: Tetranychus eggs

PredM: Motile Phytoseiidae mites

PredE: Phytoseiidae eggs

StethL: Larvae of Stethorus spp.

StethE: Eggs of Stethorus spp.

Aphid: Aphids, primarily Phorodon humuli

Anystid: Motile Anystidae mites

Values of arthropods are counts per leaf, with the exception of select dates in 2023 where arthropods were collected with the aid of a mite brushing machine. On dates when a mite brushing machine was used, a single value is included for Leaf 1, which represents the mean number of arthropods recovered per leaf in the sample for that experimental unit.

## Canopy shake sample data in Shake.csv

Year: 2021, 2022, and 2023

Date: MM/DD/YY format

Block: Replicate block indicted with Roman numerals I to VIII for the eight replicate blocks

TRT: Treatment, where 1 = nontreated, 2 = imidacloprid applied in May, and 3 = imidacloprid applied in June

Shakes: Number of bines from which shake samples were collected.

LBAdult: Aphidphagous ladybeetle adults, all species

Psyllabora: Psyllabora, typically adults

LBL: Aphidphagous ladybeetle larvae, all species

StethA: Adults of Stethorus spp.

StethL: Larvae of Stethorus spp.

MPA: Minute pirate bug adults, Orius spp.

MPN: Minute pirate bug larve, Orius spp.

Hoverfly: Syrphid spp.

LWL: Lacewing larvae

Spiders: All spiders, not identified

Anystid: Motile Anystidae mites

Hymenop: Hymenoptera, not identified

Diabrotica: Diabrotica undecimpunctata adult

DBANymph: Deraeocoris brevis, adult or nymph

Nabid: Nabidae (damsel bugs) adult or nymph

LooperL: Hop looper larvae

Hempitera: Other predatory hemiptera

Striped Thrips: Aeolothrips adults or nymph

Data for each are a count summed over the shake samples collected within a plot 

## Yield data in Yield.csv
Year: 2021, 2022, and 2023

Date: Specific date of harvest in MM/DD/YY format

Block: Replicate block indicted with Roman numerals I to VIII for the eight replicate blocks

Treatment: Imidacloprid treatment, where 1 = nontreated, 2 = imidacloprid applied in May, and 3 = imidacloprid applied in June

Strings: Number of strings harvested per plot

DM: Dry matter, expressed as a proportion

_Alpha: Percent alpha-acids, standardized to 8% moisture

_Beta: Percent beta-aicds, standardized to 8% moisture

HSI: Hop Storage Index

Dry_Yield: Yield in kg per string

Alpha_Yield: Yield of alpha-acids in kg per string

Color: 1 to 10 ordinal value for cone color

# Other Notes
Some additional data is provided which was not published in the original paper. Some code is provided for data visualizations used for preliminary quality assurance, but which were not published.
