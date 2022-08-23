# parallel_prodigal

```Prodigal``` currently does not provide a multithreaded mode, this script breaks one input fasta file into given number of fasta files,
so they can be parallelly predicted by ```Prodigal```.

The script depends on ```Prodigal``` (of course) and ```PyFasta```, both can be installed with ```conda```
```bash
conda install prodigal pyfasta
```

Run the script with
```bash
parallel_prodigal.sh inputFile outputDir numThread {tmpDir}
```