FROM rocker/verse:latest

RUN apt-get -y update

RUN Rscript -e "install.packages('BiocManager')"
RUN Rscript -e "BiocManager::install('GenomicRanges')"
RUN Rscript -e "BiocManager::install('Biostrings')"
RUN Rscript -e "BiocManager::install('rtracklayer')"
RUN Rscript -e "BiocManager::install('TxDb.Hsapiens.UCSC.hg19.knownGene')"
RUN Rscript -e "BiocManager::install('BSgenome.Hsapiens.UCSC.hg19')"
RUN Rscript -e "BiocManager::install('org.Hs.eg.db')"
RUN Rscript -e "BiocManager::install('BCRANK')"
RUN Rscript -e "BiocManager::install('seqLogo')"
RUN Rscript -e "BiocManager::install('target')"
RUN Rscript -e "BiocManager::install('BiocWorkflowTools')"
