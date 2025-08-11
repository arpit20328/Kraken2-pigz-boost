# Kraken2 Pigz Boost

A modified **Kraken2** wrapper that uses **pigz** for parallel gzip decompression, significantly speeding up gzipped FASTQ classification.

---

## 🚀 Features
- Uses **pigz** for parallel decompression of gzipped FASTQ files  
- Drop-in replacement for standard Kraken2 command  
- Achieves **~53% faster runtime** compared to Kraken2's built-in gzip handling  

---

## 📦 Installation

```bash
chmod +x kraken2_pigz_boost_arpit

```
## Pre Requiste 

pigz: Install from [conda install pigz ](https://github.com/madler/pigz)



## Usage

```bash

./kraken2_pigz_boost_arpit --db /path/to/kraken_db --threads 16 input.fastq.gz

```
