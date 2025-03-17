Metadata.txt
*************
- Project Overview
  - Dataset Name: AgaCKNER (First Kurdish Sorani Named Entity Recognition Dataset)
  - Objective: To create the first Kurdish Sorani NER dataset for advancing Kurdish Natural Language Processing (NLP) research.

----------
- Data Collection
  - Source: Rudaw Media Network (independent Kurdish media).
  - Collection Period: During August 2024.
  - Categories: Kurdistan News, Middle East News, World News, Economic News, Sports News.
  - Articles Collected: 32 per category (160 total).
  - Method: Data manually extracted from Rudaw Media Network to ensure accuracy and preserve the original Kurdish Sorani text.

----------
- Preprocessing Steps
  - Tools:
    - Kurdish Language Processing Toolkit (KLPT) [1].
    - Python string manipulation.
  - Steps:
    - Removed unwanted characters and HTML tags.
    - Eliminated English words/characters using regex.
    - Converted English numerals to Kurdish Sorani numerals.
    - Tokenized words and sentences while preserving linguistic integrity.
  - Outcome: Cleaned corpus adhering to Kurdish Sorani conventions, ready for NER tasks.

----------
- Data Format & Annotation
  - Format: CoNLL guidelines (token + entity label per row).
  - Annotation Tool: AGA NER Annotation Tool [2] (web-based, designed for Kurdish Sorani).
  - Purpose: Helps with annotating textual data in CoNLL format.

----------
- References
  1- KLPT Documentation: https://github.com/sinaahmadi/klpt.git. \n
  2- GitHub Repository: https://github.com/BakhtawarAbdalla/AgaCKNER.git (includes preprocessing code and annotation tool).

----------
- Notes
  - AgaCKNER is the first Kurdish Sorani Named Entity Recognition dataset, created to advance Kurdish NLP research.
  - For inquiries, contact [Bakhtawar Abdalla - Github: BakhtawarAbdalla | E-mail: bakhtawar.barzan95@hotmail.com].
