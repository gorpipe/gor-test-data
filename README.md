## GOR Test Data

This repository contains test data needed for running tests within the GOR repository. The following sections contain details on this data.


**External**

The "external" directory contains data from other open source projects: 

1. /bgen  
    
   This data originates from  from the bgen project found at: https://bitbucket.org/gavinband/bgen/src/default/example/
   This project is under Boost Software License v1.0.
    
2. /samtools

   This data originates from the samtools project found at: https://github.com/samtools/htsjdk
   This project is under MIT License.

3. /gvcf

   Example gvcf file retrieved from https://gatkforums.broadinstitute.org/gatk/discussion/4017/what-is-a-gvcf-and-how-is-it-different-from-a-regular-vcf
                                             
**gor**

Several example gor files used for testing:

- dbsnp files
    
        Several variations of the dbsnp data on gor format.
        
- ensgenes_exons.gorz - 
    
        Example gor file with gene exon data.
        
- example.wgs.goodcov.gorz

        Example gor file with coverage data
           
-  genes.gor & genes.gorz
    
        Example genes files on gor format containing gene information by chromosome and position.
        
-  multicolumns.gor
    
        Example gor file with multiple columns
        
-  singleposition.gorz
    
        Example gor file within only a single chromosome and position.
        
-  too_many_seeks.gor
    
        Example gor file used for testing position caching.

**nor**

Simple nor files for testing nor file handling.

**parquet**

Example parquet files contain GOR data for testing parquet file handling by GOR. Documentation on parquet files can be found at: https://spark.apache.org/docs/latest/sql-data-sources-parquet.html

**ref_mini**

Mini reference data for testing (unit and integration). The reference data is minimized by approximately a factor of 1000
   
**reports**

Example yml files for running test reports