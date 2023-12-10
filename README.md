# PDF DOI Renamer # 

This is a fork of a project called NameIt by Jose Texairia where I had made a significant contribution. This project introduces a DOI-based naming model, spearheaded by my research and implementation efforts. While an existing renaming program was in place, it was initially closed-source and reliant on proprietary software. If you want to use the software please follow the link to the original Github profile for the project. <https://github.com/jaateixeira/nameit>

## Key Contributions from Sukrit: ##

DOI-Based Naming Model: Researched and developed a cutting-edge naming model utilizing Digital Object Identifiers (DOIs) for enhanced file identification and organization.
Transition to Open Source: Played a pivotal role in making the renaming program open source, fostering collaboration and transparency within the community.


## Prerequisites ##
Make sure you have the following dependencies are fulfilled.
An active internet connection.
Habanero: A Python wrapper for the CrossRef Metadata API.
PyMuPDF: A Python bindings for MuPDF, a lightweight PDF and XPS viewer.

## How to Use ##
1. Clone the Repository
2. Run the Python Script renamer_script.py (Provide the location of the directory with PDFs or the individual PDF)
3. Let the script run and enjoy.

Note: 

- Ensure that the PDF files in your library have a DOI on the first page for accurate renaming.
- The script utilizes the CrossRef API to extract information based on the DOI.
- After running the script, your PDF files will be renamed according to the extracted information in APA (7th Formatting).

# License #

MIT license. Please acknowledge derivative works to the original project. 

# Acknowledgements 

* First created by Jose Teixeira <jose.teixeira@abo.fi>
* First contribuitions by Sukrit <sukrit@sukritpant.me>
* Support from the Academy of Finland via the DiWIL project  <see https://web.abo.fi/projekt/diwil/> 
* Support from the open-science initiatives of Åbo Akademi 
