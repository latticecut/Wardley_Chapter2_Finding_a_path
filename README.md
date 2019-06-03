# Wardley Map for Chapter 2 "Finding a path"

> "it has always been standardisation of components that has enabled creations of greater complexity" - Simon Wardley  
 
This is a Wardley Map for Chapter 2 of Simon Wardley's online book on topographical intelligence for business strategy. Full details can be found here (reading time ~24 mins): https://bit.ly/2zI1tpY 

# Motivation 

Wardley Mapping has proved a useful tool for that can serve as a basis for framing the analysis of technology maturity and helping develop business strategy. 

This is an example of visualizing Wardley Maps and Value Chain dependency networks in LaTeX. It aims to provide a simple and easy method to create, visualize and modify Wardley Maps that is consistent with best practise in collaboration, document management and version control. 

The example is based on the PGF/Ti*k*Z languages for producing vector graphics from a geometric/algebraic description. PGF is a lower-level language, while Ti*k*Z is a set of higher-level macros that use PGF and an interpreter written in TeX by Till Tantau.

Particular focus is made on the software usability and interoperability with other tools. Simple maps can be directly created in LaTeX, while more complex networks can be imported from external sources (e.g. NetworkX, QGIS, ...) although I don't go that far in simple example. 

The Map is simply a collection of different .tex files that allow you to build up the representation of a business. Whilst this is a simple example I have kept the file structure similar to a more complicated project, decomposing the final Map into different Layers, Plates and Strata and separating Vertices and Edges into different .tex files. As the practice of mapping matures it is likely that this decomposition will evolve to a standard form. 

This example makes use of tikz-network.sty from Juergen Hackl but it is entirely possible use plain Ti*k*Z. You can see an example of the final figure Figure 11 downloaded as a pdf in the folder structure. 

# Figure 8

This has been split out into one stratum, the Application Layer with two .tex files for nodes (V) and edges (E) respectively.

# Figure 11

Here we add example annotations using the "Fig11_Annotation.tex" file over the top of the Map from Figure 8. Comment out as desired. In practice a lot of the code in this file is just about styling, for example the formatting of the Key, and can be ignored during the normal mapping process. However, I have tried remain faithful to Simon's original style/rendering. 



