# Use risserlin/bcb420-base-image as a base image
FROM risserlin/bcb420-base-image:winter2024-arm64

# Install R packages
RUN R -e 'BiocManager::install("DESeq2")'
RUN R -e 'install.packages("pheatmap")'
RUN R -e 'BiocManager::install("enrichplot")'
