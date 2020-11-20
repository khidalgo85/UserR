
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![ForTheBadge
built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)
<!-- badges: end -->

# UseR! <img src="imgs/1.png" align="right" width = "120px"/>

O R é uma linguaguem muito versátil, que é amplamente usada em
diferentes áreas. Por qué R é melhor para analisar e processar nossos
dados?

Entre [aqui](https://bit.ly/3lO23pG) para ver a apresentação com algumas
das razões e exemplos do que você pode lograr aprendendo a programar em
R.

## Instalação

-   Neste [link](https://cran.r-project.org/) pode instalar a última
    versão de R (v.4.0.3)

-   Rstudio pode ser descarregado
    [aqui](https://rstudio.com/products/rstudio/download/#download)

-   Alguns pacotes

    -   `qiime2R` para leitura de arquivos de saído do **Qiime2**

<!-- -->

    ## Instala o pacote qiime2R que lê arquivos .qza (saída do QIIME2)
    if (!requireNamespace("devtools", quietly = TRUE)){install.packages("devtools")}
    devtools::install_github("jbisanz/qiime2R", force = TRUE)

-   `phyloseq`: Para análisis de microbiomas.

<!-- -->

    ## Instala phyloseq
    if (!requireNamespace("BiocManager", quietly = TRUE))
        install.packages("BiocManager")
    BiocManager::install("phyloseq")

-   `ggplot2`: Para graficar

<!-- -->

    ## Instala ggplot2
    install.packages("ggplot2")

## Uso

Os pacotes pode ser carregados como qualquer outro pacote de R:

    library(qiime2R)
    library(phyloseq)
    library(ggplot2)
