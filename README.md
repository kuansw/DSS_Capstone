# JHU Data Science Specialization Capstone Project

This Git repository contains my submission for Data Science Specialization Capstone Project.

The submission comprise of the following files: 

1. DSS_Capstone.Rmd:  The source Rmarkdown file which processes the Yelp data, runs the models and generates the 5-page report.
2. DSS_Capstone-slides.Rpres:  The source Rpres file which generates the 5-slides presentation.
3. DSS_Capstone.pdf:  The generated 5-page report in PDF format.
4. DSS_Capstone-slides-rpubs.html:  the generated 5-slides published to Rpubs.
5. 1stars_trigram-wordcloud.png
6. 5stars_trigram-wordcloud.png

To reproduce the report, put the review and business json datasets from the 
Yelp Academic Dataset in the same working directory as the DSS_Capstone, and 
run knitr.   For your information, the whole end-to-end process may take a while to complete run due to the complexity of the sentiment analysis and the amount of data to process.   On my Macbook Air, it took over 7 hours.

To reproduce the slides, the report processing must first be completed to 
generate the intermediate results files, which are then loaded in the Rpres file.
In addition, the two wordclouds png file,s which were previously generated, needs
to be in the same working directory as the Rpres file before generating.

Regards,  
  Kuan Siew Weng 
