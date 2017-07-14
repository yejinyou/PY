# CWL Generator for GATK Command Line tools

This script will generate the JSON files from the GATK documentation (found at "https://software.broadinstitute.org/gatk/documentation/tooldocs/3.5-0/" depending on the version).

To run, use the following command:

```
python generate_cwl.py version /path/to/files

(python generate_cwl.py 3.5 /home/pkarnati/cwlscripts)
```

The script will create two folders, one with the json scripts and one with cwl scripts.
