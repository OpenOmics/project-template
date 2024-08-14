# Data

The `data/` directory is intended to contain any small reference files or data to reproduce the results. By default, anything added to this directory will be ignored by `git` via our `.gitignore`. This is to ensure large files or any other sensitive data are not accidently committed. If you would like to include a large file (>=5MB), please contact the repository owner discuss the best way to include this data.

If you would like to include data in this directory, you can do so by running the following command:

```bash
# Example git command to add a file
# in this directory, by default git 
# will ignore anything in this folder. 
# You can override this behavior by 
# using the -f flag with the git add
git add -f data/counts.tsv
```
