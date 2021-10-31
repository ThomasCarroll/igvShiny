BigWig load unittest
--------------------

Added bigwig load to package and below unittest.

    library(igvShiny)
    library(shiny)
    bw_unitTestExample <- system.file(file.path("unitTests","igvShinyDemo.R"),package = "igvShiny")
    runApp(bw_unitTestExample)
