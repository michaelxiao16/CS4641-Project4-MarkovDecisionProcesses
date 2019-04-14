# Markov Decision Processes
# based on https://github.com/cmaron/CS-7641-assignments/tree/master/assignment4

## Output
Output CSVs and images are written to `./output` and `./output/images` respectively. Sub-folders will be created for
each RL algorithm (PI, VI, and Q) as well as one for the final report data.

If these folders do not exist the experiments module will attempt to create them.

Graphing:
---------

First, run the run_experiment script

python run_experiment.py --all

The same script can then be used to generate plots via:

```
python run_experiment.py --plot
```

Since the files output from the experiments follow a common naming scheme this will determine the problem, algorithm,
and parameters as needed and write the output to sub-folders in `./output/images` and `./output/report`.

