# boda-ericssoncnaiparser
Converts Ericsson 2G CNAI Configuration Profile dumps  into csv. The parser generates a separate csv file for each domain encountered in the file.

# Usage
```
usage: java -jar boda-ericssoncnaiparser.jar
Parses Ericsson CNAIv2 configuration data file to csv

 -c,--parameter-config <PARAMETER_CONFIG>   parameter configuration file
 -h,--help                                  show help
 -i,--input-file <INPUT_FILE>               input file or directory name
 -m,--meta-fields                           add meta fields to extracted
                                            parameters. FILENAME,DATETIME
 -o,--output-directory <OUTPUT_DIRECTORY>   output directory name
 -p,--extract-parameters                    extract only the managed
                                            objects and parameters
 -v,--version                               display version

Examples:
java -jar boda-ericssoncnaiparser.jar -i cnaiv2_dump.xml -o out_folder
java -jar boda-ericssoncnaiparser.jar -i input_folder -o out_folder
java -jar boda-ericssoncnaiparser.jar -i input_folder -p
java -jar boda-ericssoncnaiparser.jar -i input_folder -p -m

Copyright (c) 2018 Bodastage Solutions(http://www.bodastage.com)
```

# Requirements
To run the jar file, you need Java version 1.6 and above.