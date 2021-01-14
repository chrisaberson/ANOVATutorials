To install the package, use the following code.

    install.packages("learnr","car","lsr","ggplot2","car","ezANOVA","BayesFactor","MBESS")
    library(devtools)  
    install_github("chrisaberson/ANOVATutorials")  

To run a tutorial, use this code.

    library(learnr)  
    run_tutorial("ttest", package = "ANOVATutorials")

After you run this code, the tutorial will open in a tab on your
browser.

If this doesn’t work, you likely need to update your rtools. Go to
<a href="https://cran.r-project.org/bin/windows/Rtools/" class="uri">https://cran.r-project.org/bin/windows/Rtools/</a>
and download the most recent version (for your platform (Note: Rtools is
just for Windows, I am looking into other platforms). You may also, on
Mac OS have to install the backports package.
