# SNP calling with GATK

```bash
/home/ubuntu/bin/jdk1.8.0_102/jre/bin/java -jar /home/ubuntu/bin/picard.jar CreateSequenceDictionary R=/home/ubuntu/ref/HA412.v1.1.bronze.20141015.fasta O=/home/ubuntu/ref/HanXRQr1.0-20151230.dict
samtools faidx HA412.v1.1.bronze.20141015.fasta