# Energy Poverty Table A3 Replication

This repository replicates Appendix Table A3 from the paper:

-"Machine Learning with Administrative Data for Energy Poverty Identification in the UK"

## Environment

-Python 3.11.9

## Replication target

I replicate the performance results reported in Appendix C, Table A3 for:

-Benchmark
-COM-1
-COM-2
-Extended Model

## Files

-`ep_prediction_model_original.ipynb`: original notebook downloaded from the authors' repository
-`table_a3_replication.ipynb`: my replication notebook
-`clean_data.csv`: cleaned dataset used for replication
-`performance_metric_result.csv`: official result file provided by the authors
-`table_a3_reproduced.csv`: my reproduced Table A3 output

## Important replication note

In the released notebook, the Extended Model uses:

-`set_threshold=0.40`

However, in the published paper (Appendix C, Table A3), the Extended Model is reported with:

-`Set Threshold = 0.43`

To align the code with the published paper table, I changed the threshold from '0.40'to '0.43'in my replication notebook.

-The original value is preserved in comments in the notebook for transparency.

## Output

The final reproduced results are saved in:

-`table_a3_reproduced.csv`
