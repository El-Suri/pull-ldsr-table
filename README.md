# Extract LD score regression log table `v1.0.1`


### What does it do?
Creates a CSV table from the table in the [LD Score Regression](https://github.com/bulik/ldsc) log output file.

### How do I do it?
To run at the command line type:

`python extract_ldsc_log_table.py -f <path_to_your_log_file>` 

Options are:

 -f --file      specify path to your log file (required)

 -v --verbose   prints table to the command line (optional)

 -h --help      prints options and description before closing (optional)
 
 
 ### What do I need?
 
 * python3 (untested on python2)
 * pandas package
 * LDSC log output 
             
