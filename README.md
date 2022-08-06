# Somático EP2

A amostras WP312 agora será executado com a versão do genoma humano HG19.
A única parte que muda do EP1 é a das referências


**AS Referências do Genoma hg38 (FASTA, VCFs)**

Os arquivos de Referência: **Panel of Normal (PoN), Gnomad AF**

> https://console.cloud.google.com/storage/browser/gatk-best-practices/somatic-b37?project=broad-dsde-outreach

```bash
wget -c https://storage.googleapis.com/gatk-best-practices/somatic-b37/Mutect2-WGS-panel-b37.vcf
```

```bash
https://storage.googleapis.com/gatk-best-practices/somatic-b37/Mutect2-WGS-panel-b37.vcf.idx
```

```bash
https://storage.googleapis.com/gatk-best-practices/somatic-b37/af-only-gnomad.raw.sites.vcf
```

```bash
https://storage.googleapis.com/gatk-best-practices/somatic-b37/af-only-gnomad.raw.sites.vcf.idx
```
      

> Arquivo no formato FASTA do genoma humano hg19

Diretório Download UCSC hg19:https://hgdownload.soe.ucsc.edu/goldenPath/hg19/chromosomes/
chr9.fa.gz: https://hgdownload.soe.ucsc.edu/goldenPath/hg19/chromosomes/chr9.fa.gz

```bash
wget -c https://hgdownload.soe.ucsc.edu/goldenPath/hg19/chromosomes/chr9.fa.gz
```

