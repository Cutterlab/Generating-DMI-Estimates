Scripts for assessing through forward simulation the power of evolve and resequence experimental evolution of hybrid populations to map DMI loci. We simulate various biologically relevant parameters such as one-way versus two-way incompatibility type, number of incompatibilities, selection strength, recombination rate, and dominance interactions to determine which mapping feasibility and sensitivity. We also simulated the parameters under direct control of an experimenter, including duration of experimental evolution and number of replicate populations.

- Description of Scripts -

  Two-Loci DMI Directory

This directory contains the scripts to generate estimates of DMI loci expressed for two-loci      incompatibilities.

    Command Line Files Directory

This directory contains scripts executed at the command line.

      Generating SLiM Populations

This script generates genomic data for 500 sets of 10 replicate populations with DMI loci simulated in SLiM for a particular parameter set defined by the combination of generation timepoints (gt), selection (s) and dominance values (y) (z).

      Summarizing Estimates

This script summarizes estimate summaries from 500 estimate files generated from 10 replicate SLiM populations for a particular parameter set (defined by generation timepoint (gt), selection coefficient (s), and dominance values (y) (z).

  Neutral Files Directory

This directory contains scripts for generating neutral simulations.

    Neutral SLiM Populations

This script generates neutral populations in SLiM. It is the same as the “DMI SLiM Script” except that the loci where the DMIs usually are (2601040 bp & 31201040 bp) are neutral and confer no negative fitness effects.

    Command Script for Generating Neutral SLiM Populations

This script generates 1000 neutral populations for a given number of generations from the above SLiM script.

    Generating 2.5th and 97.5th quantiles in R

This R script determines the 2.5th and 97.5th quantiles for genomic frequencies for each locus in a neutral population 

    Command Script for Generating Quantiles

This script runs the above “Generating 2.5th and 97.5th quantiles in R” file with variable generation timepoints.

  R Files Directory

This directory contains the scripts that produce DMI loci estimates.

    Generating Estimates - OneWay

This script contains the R file that produces DMI loci estimates for a specific parameter set.

    Summarizing Estimate Files

This script retrieves the Estimate output files produced from the above script to summarize them in readable tables.

  MultiReps Directory

    SliM Populations

This script generates SLiM populations with multiple DMI pairs.

    Generating correct DMI loci and hybrid populations script

This script randomly generates 20 loci to act as DMI loci. It also instructs the generation of 300 sets of X number of replicate populations (in the below, 20 reps is define) in SLiM. It then generates estimates of DMI loci, and organizes the correct DMI loci into a table to be compared to the estimates in a separate script.

    correct loci in R

This R script defines in a table the 20 DMI loci.

    Step 1 - Generating Estimates in R

This R script generates estimates of DMI loci.

    Summarizing estimates in R

The R script takes the 300 output estimate files from the above Step 1 - Generating Estimates in R script and summarizes the estimate accuracies and precision values.
