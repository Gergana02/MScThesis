# MScThesis
This repository contains the complete data analysis framework employed in my thesis project "Longitudinal Associations Between Allostatic Load, DHEAS, and Self-Reported Sleep Quality During the Menopausal Transition "

Final fitted models are provided in `clmm_models.rds`.

Load with:

models <- readRDS("clmm_models.rds")

Available models:
- baseline_controlled_sp
- DHEAS_controlled_sp
- long_controlled_sp
- reduced_controlled_sp

For example:

summary(models$baseline_controlled_sp)
