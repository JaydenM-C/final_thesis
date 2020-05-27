*************************************
*****UQ LaTeX THESIS TEMPLATE********
*************************************
Copyright (C) 2019 The University of Queensland Graduate School
Last revision: 17 April 2019.

*************************************
*************LICENSING:**************
*************************************

The User acknowledges the existence of and agree to comply with all relevant terms and conditions. In particular:

a.	The Graduate Thesis Template has been created using open-source software, the terms of which can be found below;
b.	Access to the Template through editor programs such as Overleaf requires compliance with the terms and conditions governing those editor programs. 
c.	The Template contains content that is the intellectual property of The University of Queensland, including copyright and protected marks, which must be respected in accordance with applicable laws;
d.	The University of Queensland does not collect any private data arising from the use of the Graduate Thesis Template.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License (GNU License can be located under the GNU_License.txt file) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.

*************************************
**************SUPPORT:***************
*************************************

For support please contact training@library.uq.edu.au

If the template does not compile correctly in your LOCALLY setup distribution, check that it is up to date. Overleaf, as a cloud based service, should always be current. If you still encounter compile errors, please submit a bug report including:
    - details of your operating system (Windows, Unix, etc.), LaTeX distribution (MikTeX, etc.), and any package conflicts (including all package and versions)
    - a copy of the relevant error log(s)
    - a minimum working example of code that recreates the error

See <https://tex.stackexchange.com> for good examples of bug reports/questions.

*************************************
*********USING THE TEMPLATE:*********
*************************************

Follow the instructions below and those given in the template itself to produce a thesis with formatting that conforms to UQ's guidelines.

This template has been designed for use with Overleaf, but also can be used in a local distribution.

To use this template:
    - Compile MainThesis.tex, ensuring that you have all of the necessary packages.
    - Add or subtract the packages in LaTexPackages.tex as needed for your thesis.
    - Insert the appropriate bibstyle and .bib files into MainThesis.tex to allow BibTeX to function correctly. A Bibliography.bib file, which you may use or replace, is included in the /References directory of this template. 
    - Add each chapter as a separate .tex file using \input{} commands in MainThesis.tex. Chapter .tex files and associated figures should be kept in their own directory. 
    - Carefully read the instructional text in Preliminary.tex and Back.tex and complete these sections. FAILURE TO FOLLOW THESE INSTRUCTIONS WILL LIKELY RESULT IN THESIS REJECTION. The Back.tex file will also require editing if you are including back matter.
    - Complete your list of abbreviations and symbols in Symbols.tex .You may add Tex packages to assist this process.

*************************************
*********TEMPLATE STRUCTURE:*********
*************************************

This template contains the following:
    - Eight directories: Abstract, Appendix, Chapter1, Chapter2, Conclusion, Examples, PreliminaryAndBackPages and References. To reduce clutter, the directories contain source files eg .tex and figure files for each section, as indicated. These make up the body of the thesis. Edit and duplicate as necessary.
    - MainThesis.tex is the main file which receives the others as inputs.
    - uqthesis.cls loads necessary packages, sets the page and heading styles, defines the line spread and redefines the \sqrt{} command to change the default length of white space in order to improve readability. Comment out the relevant code in the uqthesis.cls file if you prefer not to have these white space changes.
    - uqtitle.sty sets the title page style and defines storage commands (\currentdegrees, \submittedfor, etc.)
    - LaTexPackages.tex defines packages and some optional text macros. Some elements of this file may be altered if required. The included packages are listed below.
    - AuthorDeclaration.tex is the author declaration that must appear verbatim in your final thesis. DO NOT EDIT!
    - UQLogo.jpg is the UQ shield logo. Alter the class file if you want to use .eps filetype.
    - OrcidLogo.jpg is the Orcid logo. Alter the class file if you want to use .eps filetype. 
    - abbrv-unsrt.bst is a numerical bibliographic citation style by E.Krepska which provides short numerical citations in order of citation. This is just an example, and you may choose your preferred style.
    - GNU_License.txt is a copy of GNU General Public License v3

The /PreliminaryAndBackPages directory contains three .tex files: 
    - Preliminary.tex contains/produces the front matter, everything prior to the body of the document. Instructional comments in this section MUST be suppressed in the final thesis by using the \documentclass[final]{uqthesis} option in the Mainthesis.tex file.
    - Back.tex contains the optional back matter
    - Symbols.tex provides space for the list of abbreviations and optional list of symbols.

The files within the /Examples directory are for reference only. DO NOT INCLUDE any of these files in your thesis. The directory contains the following example files: 
    - ExampleOfCitations.tex contains/produces the citation process.
    - ExampleOfEquations.tex contains/produces the mathematical equation writing process.
    - ExampleOfFigures.tex contains/produces the figure inserting process.
    - ExampleOfFlawCharts.tex contains/produces the flowchart writing process.
    - ExampleOfTables.tex contains/produces the table making process.

Abstract.tex in /Abstract contains instructions for compiling a stand-alone version of the abstract for submission purposes.

*************************************
**************PACKAGES:**************
*************************************

The LaTexPackages.tex file contains the following packages:

**Essential packages - DO NOT DELETE**
    - uqthesis class
    - uqtitle
    - memoir class
    - mathptmx
    - booktabs
    - longtable
    - url
    - hyperref
    - memhfixc
    - setspace
    - comment

**OPTIONAL packages you can alter/add as needed**
    - cite
    - rotating
    - pdfpages
    - wrapfig
    - bm
    - upgreek
    - dsfont
    - mathtools
    - framed
    - microtype
    - marvosym
    - color
    - transparent
    - placeins
    - mdframed, mdwlist
    - graphicx
    - float
    - longtable
    - mathdots
    - eucal
    - array
    - stmaryrd
    - amsthm
    - pifont
    - lipsum
    - enumerate
    - geometry
    - amsmath
    - amssymb
    - utf8
    - fancyhdr
    - blindtext
    - tikz
    - figuresright

*************************************
**********ACKNOWLEDGEMENTS:**********
*************************************

The latest version of this template has been developed by The University of Queensland Library as a Student-Staff Partnerships project. Thank you to Elena Danilova, Trinity McNicol, James Nicholson, Hanna Reinebrant, Sanjib Mondal, Jan Mairhoefer, Preeti Vayada, Luke Gaiter, and Nick Fitt for your involvement with this project.

Previous contributors include Paul Cochrane, Will Petterrsen, James Bennett,  Christiaan Bekker, Thomas Bell, Catxere Andrade Casacio, Nicolas Mauranyapin, Varun Prakash, and Alexander Stilgoe.
