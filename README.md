### == PURPOSE & USAGE ==

Interactive shell with X11 forwarding for SLURM.


Run srun.x11 with the usual sbatch arguments, but DO NOT give a program to run.
When your job starts, you'll find yourself using an interactive shell which has
proper X11 forwarding enabled.

for example on **farm**
```
srun.x11 -p bigmemh --mem 32000
### run R
R
### inside R console
hist(1:10)
### a histogram should be popped up.
```

----

## == Author & Credits ==

Scripts were written by  Pär Andersson (National Supercomputer Centre, Sweden)
and published in the SLURM FAQ.

==
