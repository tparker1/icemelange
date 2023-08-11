# ICe Mélange

## Team Members

The following people contributed to our project throughout the week:
* Project lead: Aman KC
* Project lead: Tara Parker
* Project lead: Wanwei Huang

## Project Goals

![melange](https://github.com/tparker1/icemelange/assets/39869129/e7c753d9-7f6a-4332-a0c1-b02d86b97bf3)
    Fig: Ice mélange                                                                                                                                         
    *Credit: Joe MacGregor / NASA*

Our broad project goal was to use IceSat-2 data to determine the thickness of mélange along the fjord of Sermeq Kujalleq (Jakobshavn Isbræ).
Our team was interested in exploring different resources to access ICESat-2 data, learning about ATL products, and recognize which products would be useful to get ice mélange thickness.
At the same time, also determining what the limitations are based on study site and temporal interests. Collaboration using github and efficent sharing of code was what we all aspired for at the beginning.

## Project Outcomes

* We explored ATL 10/06/03 datasets (using earthdata/CMR/earthaccess/icepyx) and Explored sliderule for getting freeboard data for atl03 datasets.
* We used openaltimetry to see where there is data on ice melange areas.
* We created timeseriers for fjord using h_mean ATL06 (sliderule-processed) data and investigated outliers in the data.
* We compared high-med-low cnf data and calculate geoid height and substract it from h_mean to get closer to actual height.
* We identified data gap in ATL10 near coast and evolved project focus to filling data gaps in ATL10 around coastline.
* We wrote a Jupyter notebook that pulls ATLO6 data using Slide ride (outside of land ice) and estimates the height of ice from reference ellipsoid.
* We also developed a workflow to convert height of ice above the reference ellipsioid to freeboard height using [geoid height](https://github.com/ICESAT-2HackWeek/3D_CRS_Transformation_Resources) and tidal using [pyTMD](https://pytmd.readthedocs.io/en/latest/api_reference/compute_tide_corrections.html).
* [Example Workflow Jupyter Notebook](your notebook url here).


## Future Efforts

* Explore ATL03 data and other options for near-coast ice thickness data.
* Extend and refine the timeseries to investigate ice mélange seasonality.
* Process tidal data to correct the estimated sea ice height.  

* 
Have you built any great new collaborations you anticipate continuing after the Hackweek?
Is your team planning to keep meeting to continue hacking or draft a conference abstract or proposal?
Did you start doing some work that relates to your research and enables you to contribute to shared tools for working with ICESat-2 data products?
Please share your hopes and plans for the future here!
