# T5 Text-to-SQL Model
Running Spider and IDSpider using T5 model.

# IDSpider: Indonesian Standard Dataset for Text-to-SQL

## Abstract
This research presents IDSpider, a new standard dataset for Text-to-SQL research in Indonesian, developed by translating the well-established Spider dataset into Indonesian. Text-to-SQL is a critical technology that bridges the gap between natural language processing (NLP) and database management systems, allowing non-technical users to retrieve data from databases using simple, natural language queries. 
However, most existing datasets are in English, leaving nonEnglish languages, especially Indonesian, underrepresented in the field. 
This paper describes the challenges encountered in translating both natural language questions and SQL queries, given the need for precision in maintaining SQL syntax and database structure integrity. We implemented a four-stage process consisting of Extraction, Translation, Cleaning, and Conversion to generate the IDSpider dataset. 
Furthermore, we tested the performance of the BRIDGE model on both the original Spider dataset and the translated IDSpider dataset. Results show that while the BRIDGE model performs well on Spider, its performance drops significantly when applied to IDSpider, primarily due to language differences and translation complexities. 
This research establishes the first benchmark for Indonesian Text-to-SQL tasks and lays the groundwork for further improvements in cross-lingual natural language interfaces for databases.

## Citation

If you find our work useful, please cite

### BibTex
```
@INPROCEEDINGS{10956918,
  author={Abdiansah, Abdiansah and Yusliani, Novi and Fathoni, Fathoni and Nizar, Muhammad Fazri and Salsabella, Aulia and Davi, Agi Agustian},
  booktitle={2024 Ninth International Conference on Informatics and Computing (ICIC)}, 
  title={IDSpider: Indonesian Standard Dataset for Text-to-SQL}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Bridges;Structured Query Language;Translation;Accuracy;Semantics;Benchmark testing;Syntactics;Natural language processing;Cleaning;Standards;Text-to-SQL;Spider;IDSpider;SQL Query Generation;Dataset Translation},
  doi={10.1109/ICIC64337.2024.10956918}}
```

### PlainText
```
A. Abdiansah, N. Yusliani, F. Fathoni, M. F. Nizar, A. Salsabella and A. A. Davi, "IDSpider: Indonesian Standard Dataset for Text-to-SQL," 2024 Ninth International Conference on Informatics and Computing (ICIC), Medan, Indonesia, 2024, pp. 1-6, doi: 10.1109/ICIC64337.2024.10956918. keywords: {Bridges;Structured Query Language;Translation;Accuracy;Semantics;Benchmark testing;Syntactics;Natural language processing;Cleaning;Standards;Text-to-SQL;Spider;IDSpider;SQL Query Generation;Dataset Translation},
```
