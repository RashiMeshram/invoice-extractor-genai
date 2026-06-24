# Invoice Data Extractor

# Project Desciption
This project is an automated Python data extraction pipeline designed to process various layouts of invoice PDFs, clean their raw text format, and extract structured accounting fields.
The application maps data dynamically across differing vendor designs into a standardized JSON format. If fields are absent in the source invoice, the engine automatically and gracefully flags them as null instead of generating placeholder strings or hallucinating mock details.

# Tested Invoice Layouts
This repository contains end-to-end extraction results tested across three highly distinct invoice types:

1. Defmacro Software Pvt. Ltd (Service Layout)
2. SSLEEK BILL / SC Aissac SRL (Export/Product Layout)
3. *Alpha Computer (Hardware/Retail Supply Layout)

# How to Install Dependencies
To configure your local execution workspace environment to run this notebook script, install the verified dependency packages specified in the root index folder using pip:

```basH
pip install -r requirements.txt
