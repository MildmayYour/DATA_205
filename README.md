Data tool for the Safe Routes to School part of the Montgomery County Safe Streets Act

Project question 1: What are some important characteristics of crashes in Montgomery County where drivers hit non-adult (aged 0-18) non-motorists (pedestrians, bicyclists, etc.)?

Project question 2: How many crashes might require infrastructure reviews by the Montgomery Department of Transportation, under the Safe Routes to School provision of the Safe Streets Act, when the law goes into effect on July 1, 2025?

Data source: Data Montgomery Crash Open Data Non-motorist file https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Non-Motorists-Data/n7fk-dce5

Data source: Data Montgomery Crash Open Data Incident file https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Incidents-Data/bhju-22kf

Data source: Maryland State Police Crash Data Download https://mdsp.maryland.gov/Pages/Dashboards/CrashDataDownload.aspx

Additional data source: geospatial data on school bus stops and school walk zones, from Montgomery County Public Schools, via a Maryland Public Information Act request

Additional data source: geospatial data on county-established school zones, from Montgomery County Department of Transportation, via a request to the Montgomery County Vision Zero Coordinator

FinalProjectwebscrape.rmd: R markdown file for scraping the Maryland State Police data from a dynamic website, but it only partially works

FinalProjectFirstFile.rmd: R Markdown file ingesting the crash data, wrangling it, and producing an output file for geospatial processing

Model1.py: the Python code for the geospatial processing model in ArcGIS Pro

Model1.svg: an image of the geospatial processing model in ArcGIS Pro

Schoolbusstops.lpkx: the ArcGIS Pro feature layer with the school bus stops with a 100-foot buffer, for geospatial processing

Schoolzones.lpkx: the ArcGIS Pro feature layer with the county-established school zones with a 100-foot buffer, for geospatial processing

Walkzones.lpkx: the ArcGIS Pro feature layer with the walk zones, for geospatial processing

FinalProjectSecondFile.rmd: R Markdown file ingesting the data after geospatial processing, wrangling it, and producing an output file identifying potential Safe Routes to School crashes requiring infrastructure review

Final and data story.pdf: the final PowerPoint presentation and data story

Final Report.docx: the written final report

datatable.csv: the first output file (using data from the 12/8/2023 Data Montgomery update)

outputfile.csv: the second output file (after the geospatial processing)
