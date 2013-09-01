ePiSaT-ecosystem-Production-in-Space-and-Time
=============================================

Ecosystem Production in Space and Time (ePiSaT) models Gross Primary Production (GPP) across the Australian continent from OzFlux flux tower data, gridded climate and satellite (MODIS) data. ePiSaT can be used to estimate ecosystem variables by partitioning OzFlux eddy covariance data to estimate GPP, light use efficiency (LUE), the maximum rate of carboxylation (Amax) etc.  Once determined, the ePiSaT-modelled variables can be used in the well-founded and tested LUE approach to estimate GPP. Sample OzFlux data from Howard Springs is provided; ePiSaT requires the user to provide fAPAR, observed radiation, temperature and humidity data.

Australian National Data Service (ANDS)
=============================================
This project is supported by the Australian National Data Service (ANDS). ANDS is supported by the Australian Government through the National Collaborative Research Infrastructure Strategy Program and the Education Investment Fund (EIF) Super Science Initiative. For more information visit the ANDS website ands.org.au and Research Data Australia services.ands.org.au


INSTALLATION INSTRUCTIONS
=============================================

Once downloaded, you can install episat using the following terminal command.

R CMD INSTALL episat_1.0.tar.gz

Alternatively, from an R GUI go the package manager and follow the prompts to install a package from source.


GETTING STARTED IN R
=============================================

Once installed, from an R command prompt, run the following code:

library(episat)
?episat     # <-- for help and how to use the package.


SOFTWARE BLOG
=============================================
More information on the background of the project and the ePiSaT team can be found at: http://episat-software.blogspot.com


LICENSE
=============================================
This work is licensed under a Creative Commons Attribution 3.0 Attribution-NonCommercial- CC BY-NC URL: http://creativecommons.org/licenses/by-nc/3.0/legalcode SUMMARY: This license lets others remix, tweak, and build upon your work non-commercially, and although their new works must also acknowledge you and be non-commercial, they don't have to license their derivative works on the same terms.

REQUIRED ATTRIBUTION : DOI XXX.XXX.XXXX.XXX # Coming soon! AUTHORS: Bradley Evans, Colin Prentice, Tyler W. Davis, Xavier Gilbert ORGANISATION: Macquarie University, Sydney Australia 

REFERENCE: Evans, B.J., Prentice, I.C., Davis, T.W., Gilbert, X., 2013, Ecosystem Production in Space and Time, http://episat-software.blogspot.com.au

EXAMPLE: You wish to use this code or data in your own work, a peer reviewed journal article, then you need to attribute the work by referencing published article listed above and/ or the DOI (i.e. for output data only).

Contact the author if you have any questions.

MAINTAINER: bradley.evans << at >> mq.edu.au
