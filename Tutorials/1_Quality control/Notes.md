# Counting fastq reads in a file

Look at the raw reads in a gzipped fastq file use **zcat** (gzcat on mac) or just
**cat** if the file is unzipped.

**zcat raw_data.fastq.gz | head**

However to see one read over 4 lines is kind of inconvenient, so to print out the output in one line use the paste command

**zcat raw_data.fastq.gz | paste - - - - | head**

to count reads in the gzipped fastq file, count all lines and divided that by 4 with bench calculator

**echo $(zcat raw_data.fastq.gz | wc -l) / 4 | bc**
