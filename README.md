# A Natural Language Processing Approach to Complexity Assessment in Ancient Health Literature
This is a repository for the paper: Quaresma et al. (to appear). "A Natural Language Processing Approach to Complexity Assessment in Ancient Health Literature".

## Content of the repository
This repository contains the following files:

	- Gazetas-MOD-PAD-NILC-Metrix.txt
	- Semedo-MOD-PAD-NILC-Metrix.txt
	- Vieira-MOD-PAD-NILC-Metrix.txt
	- Gazetas-Semedo-Vieira-NILC-Metrix.csv

## Description of the content
The three TXT files contain the modernised versions of the texts. These are the files that were used to get complexity metrics using NILC-Metrix.

The CSV file contain the metrics from NILC-Metrix for all TXT files, with the addition of a Category column, which indicates whether the metric was used or not, and how it was interpreted. Here is a description for what can be found in each column of the CSV file:

- ID: indicates a unique id for the metric.
- Group: indicates to which group of metrics to which the specific metric belongs.
- Metric: indicates a unique name for the metric.
- Description: Gives a brief description of what the metric evaluates in the text.
- Gazetas: contains the metrics for the file "Gazetas-MOD-PAD-NILC-Metrix.txt" 
- Semedo: contains the metrics for the file "Semedo-MOD-PAD-NILC-Metrix.txt"
- Vieira: contains the metrics for the file "Vieira-MOD-PAD-NILC-Metrix.txt"
- Category: indicates whether the metric was used or not, and how it was used for getting the results shown in the paper. These are the possible values for this column:
	- S: the metric was used, and the higher the value, the more complex is the text.
	- I: the metric was used, and the higher the value, the less complex is the text.
	- X: the metric was not used.
