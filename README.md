# Genomics
## Geomics and metagenomics workshop course material

**Day 1**
* Quality Control of Sequence data
* Artemis viewer

**Day2**
* Mapping sequence data
* Genome Assembly

**Day 3**
* Genome Annotation

**Day 4**
* Metagenomics

**Instructions**

The course website is found here: [http://41.89.129.26/eanbit2020/]

Download the file eanbit2020.tar.gz from the site to your home directory on the server where you want to work.

  [wget http://41.89.129.26/eanbit2020/eanbit2020.tar.gz .]

Uncompress the file:

  ``tar zxvf eanbit2020.tar.gz``

Change to the eanbit2020 directory and you will see the four folders with the tutorial instructions and data for the course.

Create a new Bioconda environment for the course to install all the necessary software needed for the course using Anaconda.

  ``conda create --name eanbit python=2.7``

Activate the newly created eanbit environment:

  ``conda activate eanbit``

Install the following packages in the eanbit environment:

``  conda install -c bioconda fastqc``

 `` conda install -c bioconda artemis``
  
`` conda install -c bioconda trimmomatic``
  
 `` conda install -c bioconda bwa``
  
  ``conda install -c bioconda samtools``
  
  ``conda install -c bioconda bcftools``
  
  ``conda install -c bioconda velvet``
  
  ``conda install -c bioconda blast``
  
  ``conda install -c bioconda ratt``
  
  ``conda install -c bioconda augustus``
  
  ``conda install -c bioconda tophat``
  
  ``conda install -c bioconda cufflinks``
  
 `` conda install -c bioconda gatk``
  
  ``conda install -c hcc abacas``
