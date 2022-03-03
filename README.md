# High Quality Stream Evaluation Framework

## Proposed Project Abstract

Significant progress has been made to clean up rivers since the passage of the 1972 Federal Water Pollution and Control Act amendments, more commonly referred to as the Clean Water Act, fifty years ago. However, since that time much of the focus has been on restoring waste-receiving streams with overt pollution problems which has left high quality streams vulnerable and open to degradation.  High quality streams support aquatic species not found in streams with higher levels of pollution ([Bellucci et al 2011](https://portal.ct.gov/-/media/DEEP/water/water_quality_management/monitoringpubs/Bellucci-et-al-2011-Northeastern-Naturalist.pdf)) along with a wide array of critical ecosystem services that benefit the social and economic well-being of humans ([EPA 2012](https://www.epa.gov/sites/default/files/2015-10/documents/economic_benefits_factsheet3.pdf)).  Preliminary work conducted in Connecticut suggests the possible reduction of species sensitive to pollution in some high quality streams sampling sites monitored over the the past 30 years ([Eltz & Beauchene 2020](https://portal.ct.gov/-/media/DEEP/fishing/fisheries_management/Trout-Research-and-Management/Probabilistic-Sampling-of-Wild-Brook-Trout-Occurrence-in-Stream-Survey-Samples-Final-05082020.pdf), [Becker 2021a](https://marybecker.github.io/Biointegrity/), [Becker & Bellucci 2021](https://marybecker.github.io/BioVariability/)). 

This project will seek to develop and effectively communicate modernized landscape level assessment methods that continue to augment the success of the Clean Water Act in the State of Connecticut.  Using existing biological and land cover datasets I will develop methods to identify high quality streams.  This includes first using biological datasets to identify waters that support sensitive species typically found in areas that are least disturbed by human activity.  Next I will calculate and identify the landscape features in the drainage basins and catchments that contribute to high quality biological samples.  Finally I will develop a model using these landscape characteristics to predict the likelihood of stream catchments where samples have not been collected.  I will use these predictions  to identify those high quality streams that are most vulnerable to degradation if human disturbance is increased in those catchments.  

This information could be used by aquatic resource managers, decision makers and the public to prioritize preservation efforts, as well as support management to prevent further degradation in these streams and implement anti-degradation measures under the Clean Water Act.  An interactive web-mapping application will be developed to convey this data on high quality streams and drainage systems to decision makers.  The application would allow for a simplified high level overview of statewide conditions, while still allowing the user to dig deeper into the site and watershed scale data through leveled zoom and click functions with popup information.  The application will display the likelihood of a stream catchment supporting high quality waters.  A slider will be used to change the predictions on the map if human disturbance is increased in a particular catchment.  This will allow for a 'what if' analysis that identifies those catchments that are most vulnerable to small increases in disturbance.

## Mock-up 3/2/22

![HQ Vulnerability](images/HQWater_Vulnerability_Mockup.jpg)

## Data Sources to Develop Model and Map

[CT DEEP Monitoring and Assessment Program Macro-Invertebrate Biological Condition Gradient Metrics](https://github.com/marybecker/bioassessment)

[CT DEEP Monitoring and Assessment Program Fish Biological Condition Gradient Metrics]()

[CT DEEP Stream Flow Classifications – Class 1 – Free Flowing Streams](https://ctdeep.maps.arcgis.com/apps/Minimalist/index.html?appid=97f2377907824234ae9e5b964ddc28c3)

[CT DEEP Cold Water Habitat Data](https://ct-deep-gis-open-data-website-ctdeep.hub.arcgis.com/maps/CTDEEP::cold-water-sites-set/about)

[US EPA Predicted Background Conductivity Data](https://epa.maps.arcgis.com/home/item.html?id=540abb1d015b4bd2b87d30f4c28a58cb&view=table#overview)

[National Water Quality Monitoring Council Water Quality Portal](https://www.waterqualitydata.us/)

[US EPA Stream Cat Dataset](https://www.epa.gov/national-aquatic-resource-surveys/streamcat-dataset-0)

[UCONN CLEAR Changing Landscape and Forest Fragmentation Datasets](https://clear.uconn.edu/projects/landscape/index.htm)

## Methods - Draft Data Analysis Notes

In progress exploratory analysis notes:   https://marybecker.github.io/HQStreamEval/analysis/bcg_data_exploration.html

In progress identify high quality biological stream sample notes:   https://marybecker.github.io/HQStreamEval/analysis/bcg_2_high_quality_streams.html

In progress land cover data processing:   https://github.com/marybecker/HQStreamEval/blob/main/analysis/lc_catchment_stats.R

## Literature Cited / Gathering to Explore Further

[Ahearn, E.A., 2010, Regional regression equations to estimate flow-duration statistics at ungaged stream sites in
Connecticut: U.S. Geological Survey Scientific Investigations Report 2010–5052, 45 p](https://pubs.usgs.gov/sir/2010/5052/pdf/sir2010-5052_web.pdf)

[Bellucci, C.J., Becker, M., Beauchene, M. 2011. Characteristics of macroinvertebrate and fish communities from 30 least disturbed small streams in Connecticut. Northeastern Naturalist 18:411-444](https://portal.ct.gov/-/media/DEEP/water/water_quality_management/monitoringpubs/Bellucci-et-al-2011-Northeastern-Naturalist.pdf)

[Davies, S.P., and S.K. Jackson. 2006. The Biological Condition Gradient: A descriptive model for interpreting change in aquatic ecosystems. Ecological Applications 16:1251–1266.](https://doi.org/10.1890/1051-0761(2006)016[1251:TBCGAD]2.0.CO;2)

[Elith, J. and J.R. Leathwick.  2009.  Species Distribution Models:  Ecological Explanation and Prediction Across Space and Time.  Annual Reviews of Ecology, Evolution, and Systematics 60:677-697](https://doi.org/10.1146/annurev.ecolsys.110308.120159)

[Eltz, B., and M. Beauchene. 2020. A random revisit of the Statewide stream survey project: A focus on Wild Brook Trout. CT DEEP, Bureau of Natural Resources. Hartford, CT.](https://portal.ct.gov/-/media/DEEP/fishing/fisheries_management/Trout-Research-and-Management/Probabilistic-Sampling-of-Wild-Brook-Trout-Occurrence-in-Stream-Survey-Samples-Final-05082020.pdf)

[Gerritsen J, Jessup B. 2007. Calibration of the biological condition gradient for high gradient streams of Connecticut. Report prepared for US EPA Office of Science and Technology and the Connecticut Department of Environmental Protection. TetraTech, Maryland ](https://portal.ct.gov/-/media/DEEP/water/water_quality_management/monitoringpubs/Gerritsen-and-Jessup-2007-Calibration-of-the-BCG-for-High-Gradient-Streams-of-CT.pdf)

[Hill, R.A., Weber, M.H., Leibowitz, M.H., Olsen, A.R., Thornbrugh, D.J. 2016. The Stream-Catchment (StreamCat) Dataset: A Database of Watershed Metrics for the Conterminous United States. JAWRA Journal of the American Water Resources Association, 52(1), 120-128. doi: https://doi.org/10.1111/1752-1688.12372](https://doi.org/10.1111/1752-1688.12372)

[Hill, R.A., Carlisle, D.M, Hawkins, C.P.  2013. Predicting thermal reference conditions in USA streams.  Freshwater Science 32(1): 39-55](https://www.journals.uchicago.edu/doi/10.1899/12-009.1)

[Lovelace, R., Nowosad, J., Muenchow J. 2019.  Geocomputation with R.  CFC Press](https://geocompr.robinlovelace.net/index.html)

[Olson, J.R. and Cormier, S.M. 2019.  Modeling spatial and temporal variation in natural background specific conductivity. Environmental Science and Technology.](https://dx.doi.org/10.1021/acs.est.8b06777)

[Stoddard J.L., Van Sickle J., Herlihy A.T., Brahney J., Paulsen S., Peck D. V., et al. 2016. Continental-Scale Increase in Lake and Stream Phosphorus: Are Oligotrophic Systems Disappearing in the United States? Environmental Science and Technology 50, 3409–3415. ](https://pubs.acs.org/doi/abs/10.1021/acs.est.5b05950)

[Stoddard, J. L., Larsen, D. P., Hawkins, C. P., Johnson, R. K., Norris, R. H., 2006. Setting expectations for the ecological condition of streams: the concept of reference condition. Ecol. Appl. 2006, 16 (4), 1267−1276](https://doi.org/10.1890/1051-0761(2006)016[1267:SEFTEC]2.0.CO;2)

[U.S. Environmental Protection Agency (EPA). 2016. A Practitioner’s Guide to the Biological Condition Gradient:A Framework to Describe Incremental Change in Aquatic Ecosystems. EPA-842-R-16-001. U.S.Environmental Protection Agency, Washington, DC. ](https://www.epa.gov/sites/default/files/2016-02/documents/bcg-practioners-guide-report.pdf)

[U.S. Environmental Protection Agency (EPA). 2012. The Economic Benefits of Protecting Healthy Watersheds Fact Sheet.  EPA 841-N-12-004. Office of Wetlands, Oceans, and Watersheds. Washington, D.C.](https://www.epa.gov/sites/default/files/2015-10/documents/economic_benefits_factsheet3.pdf)

[U.S. Environmental Protection Agency (EPA). 2012.  Identifying and Protecting Healthy Watersheds:  Concepts, Assessments, and Management Approaches.  EPA 841-B-11-002. Office of Wetlands, Oceans, and Watersheds. Washington, D.C.](https://www.epa.gov/sites/default/files/2015-10/documents/hwi-watersheds-complete.pdf)
