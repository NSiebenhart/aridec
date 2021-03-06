Instructions for the initConditions.csv file:

The initConditions.csv file contains all information related to initial conditions of litter used in the experiment.

species: current name checked in the Tropicos data base (www.tropicos.org). If mixture of species, enter "mixture" and if average value for different species, enter "mean". In both cases, specify all the species in the metadata.yaml file variables section, at "varDesc". If they use a species more than once as different treatments (e.g.: when different samples of the same species have different litter chemistry, or if they use different plant parts), just add numbers to the name in ascendant order (i.e.: Arabidopsis thaliana1, Arabidopsis thaliana2, etc.). In such case, specify in varDesc the difference between each litter type.

type: valid options are "deciduous" or "evergreen" (for woody plants) and "forb" (eudicots) or "graminoid" (monocots) (for herbaceous plants).

N-fixer: yes or no. Check this information on the NodDB: https://doi.org/10.1111/jvs.12627

material: valid options are leaves, green leaves, homogenized leaves, crushed leaves, prematurely senesced leaves, leaves, leaflets, sheaths, stems, photosynthetic stems, terminal shoots, pods, aboveground parts, roots, fine roots, live roots. If they report the material used was recently senesced, leave unspecified. If they report otherwise, use the specific options here detailed. When they don't report whether the material is senesced or not, just use the organ name (leaves, roots, shots, etc.). If they use a mixture of aboveground parts (e.g.: leaves and shoots), use aboveground parts.

amount: amount of litter inside litter bags in grams.

All elements and organic compounds (e.g.: lignin, cellulose, etc.) must be expressed as percentage.

SLA must be in mm2 mg-1.

If a litter trait is not reported, leave blank.
