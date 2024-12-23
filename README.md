# Receipt OCR
In this project, we aim to use existing Optical Character Recognition (OCR) technology, such as Tesseract (https://github.com/tesseract-ocr/tesseract) to extract text from receipt images. Once the text is extracted, we apply Named Entity Recognition (NER), a part of Natural Language Processing (NLP), using tools like spaCy (https://spacy.io/) classify important information into predefined categories relevant to receipts. These categories include details like merchant names, dates, and total amounts, allowing us to efficiently organize and analyse receipt data.

## Team
* [Fabian Dubach](https://github.com/FabianDubach)
* [Yannick Frischknecht](https://github.com/ynkf)
* [Timon Schmid](https://github.com/xXTime-OnXx)

## Scientific Report
The scientific report is written with typst in its online editor.

[Typst - DSPRO1 - Receipt OCR](https://typst.app/project/rs36toeDbhw387QveWmAnS)

## Different types of receipts
This section provides an overview of the various formats and structures of receipts. It outlines common cases, specialized formats and rare exceptions, detailing the arrangement of elements such as item names, quantities, prices, and additional metadata like money saved or classifications.

---

**Most common cases:**

(Quantity) (Name) (Price)

(Name) (Quantity) (Price)

(Name) (Quantity) (Price/Unit) (Price)

(Name) (Price)

---

**Migros E-receipts:**

(Name) (Quantity/Weight) (Price/Unit) (Money saved) (Price) (Classification)

---

**Rare cases:**

(Article Count) (Quantity) (Name) (Price)

---
