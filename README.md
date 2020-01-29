# boda-ericssoncnaiparser
Converts Ericsson 2G CNAI Configuration Profile dumps  into csv. The parser generates a separate csv file for each domain encountered in the file.

# Usage
```
usage: java -jar boda-ericssoncnaiparser.jar
Parses Ericsson CNAIv2 configuration data file to csv

 -c,--parameter-config <PARAMETER_CONFIG>   parameter configuration file
 -h,--help                                  show help
 -i,--input-file <INPUT_FILE>               input file or directory name
 -o,--output-directory <OUTPUT_DIRECTORY>   output directory name
 -p,--extract-parameters                    extract only the managed
                                            objects and parameters
 -v,--version                               display version
 -v1,--version1                             process cnai version 1

Examples:
java -jar boda-ericssoncnaiparser.jar -i cnaiv2_dump.xml -o out_folder
java -jar boda-ericssoncnaiparser.jar -i input_folder -o out_folder
java -jar boda-ericssoncnaiparser.jar -i input_folder -p
java -jar boda-ericssoncnaiparser.jar -i input_folder -p -m

Copyright (c) 2018 Bodastage Solutions(http://www.bodastage.com)
```

# Download and installation
The lastest compiled jar file is availabled in the dist directory or get it [here](https://github.com/boda-stage/boda-ericssoncnaiparser/raw/master/dist/boda-ericssoncnaiparser.jar).

# Requirements
To run the jar file, you need Java version 1.8 and above.

# Getting help
To report issues with the application or request new features use the issue [tracker](https://github.com/boda-stage/boda-ericssoncnaiparser/issues). For help and customizations send an email to info@bodastage.com.

# Credits
[Bodastage Solutions](http://bodastage.com)  (info@bodastage.com)

# Contact
For any other concerns apart from issues and feature requests, send an email to info@bodastage.com.

# Licence
This project is licensed under Apache 2.0. See LICENCE file for details.
