# Negative-stain-data-processing-using-EMAN2

# To keep in mind during negative stain data processing
* res is limited to ~20A, even if the edges look sharp and FSC curve indicate significant higher res
* main goal of NS data collection exp is to assess the sample quality and heterogeneity
* there is no reason to collect or look at a huge amount >2/3000 asymmetric particles (2000/symmetry opertation for symmetric ones) because condition of cryo data collection will be always different
* in theory it is possible to get a <10 A data set, but in practicality experts tell it's always ~20A or >20A
* NS images have very low noise level and very high contrast. It is important to retain the high contrast signals by not specifying the X-ray pixel filter during importing micrographs
  
