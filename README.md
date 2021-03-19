To install the package, use the following code.

    install.packages("learnr","car","lsr","ggplot2","car","ezANOVA","BayesFactor","DescTools","MBESS","lavaan","Amelia","Zelig")
    library(devtools)  
    install_github("chrisaberson/ANOVATutorials")  

You may need to install the packages separately. (e.g., install.packages("learnr") then install.packages("car"). This will likely take a good bit of processing time, some of these packages are very large. 

To run a tutorial, use this code.

    library(learnr)  
    run_tutorial("ttest", package = "ANOVATutorials")
    run_tutorial("OneFactorANOVA", package = "ANOVATutorials")
    run_tutorial("Assumptions", package = "ANOVATutorials")
    run_tutorial("FactorialANOVA", package = "ANOVATutorials")
    run_tutorial("WithinANOVA", package = "ANOVATutorials")
After you run this code, the tutorial will open in a tab on your
browser.

If this doesn’t work, you likely need to update your rtools. Go to
<a href="https://cran.r-project.org/bin/windows/Rtools/" class="uri">https://cran.r-project.org/bin/windows/Rtools/</a>
and download the most recent version (for your platform (Note: Rtools is
just for Windows, I am looking into other platforms). You may also, on
Mac OS have to install the backports package.
