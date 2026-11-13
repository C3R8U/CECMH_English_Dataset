# CECMH_English_Dataset
# CECMH Dataset

**College English Collaborative Human-Machine Dataset (CECMH)**

## Overview

CECMH is an English-language dataset organized for multidimensional language diagnosis, personalized instructional content generation, and educational system evaluation. Its three connected primary datasets contain **16,700 records**: **8,500 student essay records**, **3,200 writing-feedback dialogue records**, and **5,000 personalized instruction records**. Essay records cover narrative, argumentative, and chart-description writing, with academic-year labels from **2023 to 2025**.


## Files

| File | Contents |
| --- | --- |
| `essays.csv` | Contains 8,500 English essay records with learner and prompt identifiers, essay text, reference revisions, genre, grammar-error summaries, and lexical, coherence, and structure assessment fields. |
| `essay_error_spans.csv` | Contains essay-linked grammar error annotations with one of 12 error categories, text spans, character offsets, and correction text. |
| `dialogues.csv` | Contains 3,200 writing-revision questions, contextual feedback responses, learning targets, and reply difficulty labels. |
| `instruction_pairs.csv` | Contains 5,000 learner-profile, generation-instruction, and reference-output records covering targeted exercises, graded reading, and dialogue practice. |
| `student_profiles.csv` | Contains student identifiers, initial proficiency references, four baseline ability dimensions, and assigned dataset partitions. |
| `grammar_error_taxonomy.csv` | Defines the 12 grammar-error categories with illustrative incorrect and corrected forms and category counts. |
| `field_dictionary.csv` | Lists the fields, data types, and descriptions used in the dataset tables. |
| `summary_statistics.csv` | Lists record counts and descriptive distributions by dataset, partition, and selected categories. |
