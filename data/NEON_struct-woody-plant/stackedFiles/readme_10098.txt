###################################
########### Disclaimer ############
This is the most recent readme publication based on all site-date combinations used during stackByTable.
Information specific to the query, including sites and dates, has been removed. The remaining content reflects general metadata for the data product.
All files used during stacking are listed at the bottom of this document, which includes the data publication dates.
##################################

This data package been produced by and downloaded from the National Ecological Observatory Network, managed cooperatively by Battelle. These data are provided under the terms of the NEON data policy at http://data.neonscience.org/data-policy. 

DATA PRODUCT INFORMATION
------------------------

ID: NEON.DOM.SITE.DP1.10098.001

Name: Woody plant vegetation structure

Description: Structure measurements, including height, canopy diameter, and stem diameter, as well as mapped position of individual woody plants

NEON Science Team Supplier: TOS

Abstract: This data product contains the quality-controlled, native sampling resolution data from in-situ measurements of live and standing dead woody individuals and shrub groups, from all terrestrial NEON sites with qualifying woody vegetation. The exact measurements collected per individual depend on growth form, and these measurements are focused on enabling biomass and productivity estimation, estimation of shrub volume and biomass, and calibration / validation of multiple NEON airborne remote-sensing data products. In general, comparatively large individuals that are visible to remote-sensing instruments are mapped, tagged and measured, and other smaller individuals are tagged and measured but not mapped. Smaller individuals may be subsampled according to a nested subplot approach in order to standardize the per plot sampling effort. Structure and mapping data are reported per individual per plot; sampling metadata, such as per growth form sampling area, are reported per plot. For additional details, see the user guide, protocols, and science design listed in the Documentation section in this data product's details webpage.

Latency:
The expected time from data and/or sample collection in the field to data publication is as follows, for each of the data tables (in days) in the downloaded data package. See the Data Product User Guide for more information.

vst_apparentindividual:  90

vst_mappingandtagging:  90

vst_perplotperyear:  300

vst_shrubgroup:  90

Brief Design Description: Woody Plant Vegetation Structure data are collected from distributed and/or tower plots. Each distributed plot is then sampled if at least one tree with DBH ≥ 10 cm is present, or if trees with DBH ≥ 10 cm are absent, distributed Plots are sampled if smaller woody individuals constitute ≥ 10% cover of the plot. Tower plots are sampled if at least one tree with DBH ≥ 10 cm is present in ≥ 10% of Tower Plots, or if smaller woody individuals constitute ≥ 10% of cover averaged across all Tower Plots. Within a plot, all individuals with DBH ≥ 10 cm are mapped and measured throughout the plot sampling area. Individuals with DBH < 10 cm may be mapped if they are visible to airborne remote-sensing instruments, and if stem density thresholds are met, individuals with DBH < 10 cm may be measured within nested subplots in order to standardize sampling effort across plots.
 
 At relatively mesic sites, distributed Plots are sampled every 3 years, and a minimum of n=5 tower plots are sampled annually. At continental cold and/or dry sites, distributed plots and tower plots are sampled every 3 years. At boreal sites in Alaska, distributed and tower plots are sampled every 6 years, and relocatable sites are sampled a minimum of 3 time points. At sites with seasonal senescence, the onset of sampling in a given year is triggered by senescence of canopy or understory individuals, and must be completed before growth begins the following season. At sites with no distinct season, sampling begins within ± 2 weeks of the same date, and must be completed within 4 months of onset. See NEON.DOC.000987 for more details.

Brief Study Area Description: These data are collected at all NEON terrestrial sites at which qualifying smaller woody individuals (individuals with DBH < 10 cm) are present at 10% cover or greater, or when larger individuals (individuals with DBH ≥ 10 cm) are present in 10% or more of designated plots . Functionally, sampling occurs at forested sites, and sites with shrub/scrub vegetation.

Keywords: woody plants, annual net primary productivity (ANPP), carbon cycle, archived samples, plant productivity, shrubs, material samples, biomass, plants, tree height, production, trees, vegetation, vegetation structure, net primary productivity (NPP), lianas, productivity, saplings, canopy height


DATA PACKAGE CONTENTS
---------------------

This data product contains up to 4 data tables:

vst_mappingandtagging - Mapping, identifying and tagging of individual stems for remeasurement
vst_apparentindividual - Biomass and productivity measurements of apparent individuals
vst_shrubgroup - Biomass and productivity measurements of groups of shrubs
vst_perplotperyear - Per plot sampling metadata, including presence/absence of each growthForm
If data are unavailable for the particular sites and dates queried, some tables may be absent.
Basic download package definition: The basic data package contains all measurements. An expanded data package is not available for this data product.

FILE NAMING CONVENTIONS
-----------------------

NEON data files are named using a series of component abbreviations separated by periods. File naming conventions for NEON data files differ between NEON science teams. A file will have the same name whether it is accessed via the data portal or the API.

NEON observational systems (OS) data files: NEON.DOM.SITE.DPL.PRNUM.REV.DESC.YYYY-MM.PKGTYPE.GENTIME.csv

The definitions of component abbreviations are below. See NEON.DOC.002651: NEON Data Product Numbering Convention, located at http://data.neonscience.org/documents for more information.

General conventions, used for all data products:
   NEON: denotes the organizational origin of the data product and identifies the product as operational; data collected as part of a special data collection exercise are designated by a separate, unique alphanumeric code created by the PI.

   DOM: a three-character alphanumeric code, referring to the domain of data acquisition (D01 - D20).

   SITE: a four-character alphanumeric code, referring to the site of data acquisition; all sites are designated by a standardized four-character alphabetic code.

   DPL: a three-character alphanumeric code, referring to data product processing level;

   PRNUM: a five-character numeric code, referring to the data product number (see the Data Product Catalog at http://data.neonscience.org/data-product-catalog).

   REV: a three-digit designation, referring to the revision number of the data product. The REV value is incremented by 1 each time a major change is made in instrumentation, data collection protocol, or data processing such that data from the preceding revision is not directly comparable to the new.

   HOR: a three-character designation, referring to measurement locations within one horizontal plane. For example, if five surface measurements were taken, one at each of the five soil array plots, the number in the HOR field would range from 001-005. 

   VER: a three-character designation, referring to measurement locations within one vertical plane. For example, if eight air temperature measurements are collected, one at each tower vertical level, the number in the VER field would range from 010-080. If five soil temperature measurements are collected below the soil surface, the number in the VER field would range from 501-505. 

   TMI: a three-character designation, referring to the temporal representation, averaging period, or coverage of the data product (e.g., minute, hour, month, year, sub-hourly, day, lunar month, single instance, seasonal, annual, multi-annual). 000 = native resolution, 001 = native resolution (variable or regular) or 1 minute, 002 = 2 minute, 005 = 5 minute, 015 = 15 minute, 030 = 30 minute, 060 = 60 minutes or 1 hour, 100 = approximately once per minute at stream sites and once every 5-10 minutes at buoy sites (lakes/rivers), 101-103 = native resolution of replicate sensor 1, 2, and 3 respectively, 999 = Sensor conducts measurements at varied interval depending on air mass, 01D = 1 day, 01M = 1 month, 01Y = 1 year.

   DESC: an abbreviated description of the data file or table.

   YYYY-MM: the year and month of the data in the file.

   PKGTYPE: the type of data package downloaded. Options are 'basic', representing the basic download package, or 'expanded',representing the expanded download package (see more information below).

   GENTIME: the date-time stamp when the file was generated, in UTC. The format of the date-time stamp is YYYYMMDDTHHmmSSZ.

Time stamp conventions:
   YYYY: Year
   YY: Year, last two digits only
   MM: Month: 01-12
   DD: Day: 01-31
   T: Indicator that the time stamp is beginning
   HH: Hours: 00-23
   mm: Minutes: 00-59
   SS: Seconds: 00-59
   Z: Universal Time Coordinated (Universal Coordinated Time), or UTC

ADDITIONAL INFORMATION
----------------------

Data products that are a source of this data product:

Data products that are derived from this data product:

Other related data products (by sensor, protocol, or variable measured):
NEON.DOM.SITE.DP1.10026.001, Plant foliar physical and chemical properties
NEON.DOM.SITE.DP3.30015.001, Ecosystem structure
NEON.DOM.SITE.DP1.10045.001, Non-herbaceous perennial vegetation structure
NEON.DOM.SITE.DP1.10053.001, Plant foliar stable isotopes

Protection of species of concern: At most sites, taxonomic IDs of species of concern have been 'fuzzed', i.e., reported at a higher taxonomic rank than the raw data, to avoid publishing locations of sensitive species. For a few sites with stricter regulations (e.g., Great Smoky Mountains National Park (GRSM)), records for species of concern are not published. 

Obfuscation of Personnel Information: At times it is important to know which data were collected by particular observers. In order to protect privacy of NEON technicians while also providing a way to consistently identify different observers, we obfuscate each NEON personnel name by internally linking it to a unique string identifier (e.g., Jane Doe=ByrziN0LguMJHnInl2NM/trZeA5h+c0) and publishing only the identifier.

CHANGE LOG
----------

ADDITIONAL REMARKS
------------------

Queries for this data product will return data from all dates for `vst_mappingandtagging` (since individuals maybe tagged and mapped many years before a given vegetation structure sampling bout), whereas the `vst_perplotperyear`, `vst_apparentindividual` and `vst_shrubgroup` tables will be subset to data collected during the date range specified. Data are provided in monthly download files; queries including any part of a month will return data from the entire month. In the `vst_perplotperyear` table, there should be one record per plotID per eventID, and data in this table describe the presence/absence of woody growth forms, as well as the sampling area utilized for each growth form. The `vst_mappingandtagging` table contains at least one record per individualID, and provides data that are invariant through time, including tagID, taxonID and mapped location (if applicable). Duplicates in `vst_mappingandtagging` may exist at the individualID level if errors have been corrected after ingest of the original record; in this instance, users are advised to use the most recent record. Records in `vst_mappingandtagging`may be linked to `vst_perplotperyear` via the plotID and eventID fields. The `vst_apparentindividual` table contains one record per individualID per eventID, and includes growth form, structure and status data that may be linked to `vst_mappingandtagging` records via individualID; records may also be linked to `vst_perplotperyear` via the plotID and eventID fields. For allometric measurements on tree palms and other large, nonwoody individuals, users must download the `nst_perindividual` table from the related Non-herbaceous perennial vegetation structure data product (DP1.10045.001), and join on the individualID variable. The `vst_shrubgroup` table contains a minimum of one record per groupID per plotID per eventID; multiple records with the same groupID may exist if a given shrub group is comprised of more than one taxonID. Data provided in the `vst_shrubgroup` table allow calculation of live and dead volume per taxonID within each shrub group, and records may be linked with `vst_perplotperyear` via the plotID and eventID fields.
 
 For all tables, duplicates may exist where protocol and/or data entry aberrations have occurred; users should check data carefully for anomalies before joining tables. Taxonomic IDs of species of concern have been 'fuzzed'; see data package readme files for more information.

NEON DATA POLICY AND CITATION GUIDELINES
----------------------------------------

Please visit http://data.neonscience.org/data-policy for more information about NEON's data policy and citation guidelines.

DATA QUALITY AND VERSIONING
---------------------------

The data contained in this file are considered provisional. Updates to the data, QA/QC and/or processing algorithms over time will occur on an as-needed basis.  Please check back to this site for updates tracked in change logs.  Query reproducibility on provisional data cannot be guaranteed. 
 
Starting in 2020 or earlier, NEON will begin to offer static versions of each data product, annotated with a globally unique identifier. Versioned IS and OS data will be produced by reprocessing each IS and OS data product from the beginning of the data collection period to approximately 12-18 months prior to the reprocessing date (to allow for calibration checks, return of external lab data, etc.). The reprocessing step will use the most recent QA/QC methods and processing algorithms. Versioned AOP data will be produced by reprocessing the entire AOP archive as advances in algorithms and processing technology are incorporated. This will typically occur in the northern winter months, between flight season peaks, and will be on the order of every 3 to 5 years in frequency.

POST STACKING README DOCUMENTATION
----------------------------------

Each row contains the readme filename used during stackByTable

NEON.D01.BART.DP1.10098.001.readme.20200817T124351Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T125518Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T131129Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T130053Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T131325Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T125215Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T130738Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T124557Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T125616Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T124510Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T125910Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T125544Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T130820Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T124918Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T124747Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T130020Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200817T124141Z.txt
NEON.D01.BART.DP1.10098.001.readme.20200831T134143Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125221Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125844Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T131235Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124436Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125210Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130224Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130447Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125555Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T131118Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125536Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130028Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124304Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130931Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124510Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125836Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124149Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T131017Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124021Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125632Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124040Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T125024Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124439Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124822Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T124126Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130759Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T131105Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200817T130701Z.txt
NEON.D01.HARV.DP1.10098.001.readme.20200831T130257Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125903Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125409Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125728Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125054Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T130502Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T130522Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125611Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T130348Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T130512Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125518Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125913Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T124232Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T130349Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200817T125119Z.txt
NEON.D02.BLAN.DP1.10098.001.readme.20200831T140057Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T130843Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T124129Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T124818Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T130636Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T130855Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T130551Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T125357Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T131059Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T125538Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T124912Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T125306Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T124030Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T125828Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200817T125003Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200831T130905Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20200929T173234Z.txt
NEON.D02.SCBI.DP1.10098.001.readme.20201102T134247Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T125936Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T130647Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T124811Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T124843Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T125032Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T130142Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T130140Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T130619Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T130649Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T124129Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200817T124046Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200831T133136Z.txt
NEON.D02.SERC.DP1.10098.001.readme.20200928T200834Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T125951Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T130720Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T125044Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T124913Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T130801Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T130226Z.txt
NEON.D03.DSNY.DP1.10098.001.readme.20200817T130450Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124545Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124221Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T125108Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130700Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T125940Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T125932Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130731Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124902Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124029Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124610Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130855Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130606Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130550Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124049Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130911Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124120Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T131249Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124831Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124458Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T124533Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130342Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T125008Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T130643Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200817T125017Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20200831T133422Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20201102T132941Z.txt
NEON.D03.JERC.DP1.10098.001.readme.20201109T145822Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125558Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125733Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130337Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124745Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124929Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125529Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130040Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130414Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130505Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124234Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125111Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124130Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130458Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130940Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124823Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125719Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124815Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124219Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T131342Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T125535Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124111Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124956Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T124810Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200817T130728Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20200928T201620Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20201102T134906Z.txt
NEON.D03.OSBS.DP1.10098.001.readme.20201109T150716Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130640Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124227Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130424Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124157Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130907Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130408Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130150Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T125544Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T125240Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130821Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130801Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124554Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124612Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T125248Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130946Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124720Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124345Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130724Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T125528Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124756Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T125756Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T124657Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130936Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20200817T130356Z.txt
NEON.D04.GUAN.DP1.10098.001.readme.20201102T132752Z.txt
NEON.D04.LAJA.DP1.10098.001.readme.20200817T130911Z.txt
NEON.D04.LAJA.DP1.10098.001.readme.20200817T124829Z.txt
NEON.D04.LAJA.DP1.10098.001.readme.20200817T130644Z.txt
NEON.D04.LAJA.DP1.10098.001.readme.20201102T134331Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T124038Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T130916Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T130654Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T130443Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T125341Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T124011Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T124854Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T124026Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T124553Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200817T131122Z.txt
NEON.D05.STEI.DP1.10098.001.readme.20200831T132059Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T130434Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T130738Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124749Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T125931Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124511Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124009Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124512Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124407Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T125053Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T131254Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T125006Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124018Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T130519Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200817T124731Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200831T125932Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20200928T201653Z.txt
NEON.D05.TREE.DP1.10098.001.readme.20201102T132546Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130806Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130433Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T124907Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T125412Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130615Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130929Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130936Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T124805Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130242Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T130740Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T125524Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T124155Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T131245Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200817T124717Z.txt
NEON.D05.UNDE.DP1.10098.001.readme.20200831T132629Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T125826Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T131116Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T125823Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T124502Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T124127Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T130132Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T131251Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T125117Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T124035Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T125034Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T125322Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20200817T124011Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20201102T132937Z.txt
NEON.D06.KONZ.DP1.10098.001.readme.20201109T145701Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T130745Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T125210Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T125921Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T131229Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T125606Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T130424Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T131315Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T130423Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T130226Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T125725Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T130129Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T124508Z.txt
NEON.D06.UKFS.DP1.10098.001.readme.20200817T125500Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T124955Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T125545Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T124752Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T130026Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T125025Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T130700Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20200817T125641Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20201102T132632Z.txt
NEON.D07.GRSM.DP1.10098.001.readme.20201109T145133Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124550Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124704Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124133Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T125527Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T130700Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124741Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124734Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T130111Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200817T124546Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200831T130850Z.txt
NEON.D07.MLBS.DP1.10098.001.readme.20200928T203523Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T130058Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T124256Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T124831Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T124431Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T124825Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T131226Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T125752Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T131027Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20200817T130958Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20201102T135639Z.txt
NEON.D07.ORNL.DP1.10098.001.readme.20201109T150056Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T125752Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T125744Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T124554Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T124039Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T130331Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T125506Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T124905Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T124713Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T130817Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200817T130514Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200831T125626Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20200928T195507Z.txt
NEON.D08.DELA.DP1.10098.001.readme.20201102T133250Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T124804Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T130545Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T125026Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T130120Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T124123Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T124808Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T130531Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200817T125818Z.txt
NEON.D08.LENO.DP1.10098.001.readme.20200928T202406Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T123913Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T130357Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T124240Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T130125Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T125630Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T130707Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T131257Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T130528Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200817T124751Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20200928T195612Z.txt
NEON.D08.TALL.DP1.10098.001.readme.20201102T133453Z.txt
NEON.D09.DCFS.DP1.10098.001.readme.20200817T125445Z.txt
NEON.D09.DCFS.DP1.10098.001.readme.20200817T130853Z.txt
NEON.D09.DCFS.DP1.10098.001.readme.20200817T125109Z.txt
NEON.D09.NOGP.DP1.10098.001.readme.20200817T124237Z.txt
NEON.D09.NOGP.DP1.10098.001.readme.20200817T125608Z.txt
NEON.D09.NOGP.DP1.10098.001.readme.20200817T125743Z.txt
NEON.D09.NOGP.DP1.10098.001.readme.20200817T125631Z.txt
NEON.D09.WOOD.DP1.10098.001.readme.20200817T130050Z.txt
NEON.D09.WOOD.DP1.10098.001.readme.20200817T125723Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T130224Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T125710Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T125844Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T124227Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T130614Z.txt
NEON.D10.CPER.DP1.10098.001.readme.20200817T130321Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200817T124355Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200817T124859Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200817T130041Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200817T124840Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200817T124725Z.txt
NEON.D10.RMNP.DP1.10098.001.readme.20200831T133903Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T131151Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130952Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130408Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130621Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130333Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T131142Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T125642Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T131220Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T125312Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130520Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130118Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T124546Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200817T130041Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20200928T202447Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20201102T132658Z.txt
NEON.D11.CLBJ.DP1.10098.001.readme.20201109T144822Z.txt
NEON.D12.YELL.DP1.10098.001.readme.20200817T125421Z.txt
NEON.D12.YELL.DP1.10098.001.readme.20200817T130554Z.txt
NEON.D12.YELL.DP1.10098.001.readme.20200817T130254Z.txt
NEON.D12.YELL.DP1.10098.001.readme.20200817T123918Z.txt
NEON.D12.YELL.DP1.10098.001.readme.20200817T130237Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T130310Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T125039Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T125625Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T131228Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T124419Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T124806Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T130423Z.txt
NEON.D13.MOAB.DP1.10098.001.readme.20200817T130104Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T125414Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T125230Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T124739Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T130931Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T130045Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T130653Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T125455Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200817T125739Z.txt
NEON.D13.NIWO.DP1.10098.001.readme.20200831T125939Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124454Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124411Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T125259Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124509Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T125241Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124812Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T130612Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124527Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124738Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124049Z.txt
NEON.D14.JORN.DP1.10098.001.readme.20200817T124114Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T130238Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T124721Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T131047Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T125427Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T125740Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200817T124113Z.txt
NEON.D14.SRER.DP1.10098.001.readme.20200831T131927Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T131116Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T125440Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T131226Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T130123Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T124520Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T125921Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T130605Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T125820Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T130119Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T124102Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T124459Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T131042Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T130614Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T130615Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200817T125335Z.txt
NEON.D15.ONAQ.DP1.10098.001.readme.20200831T131251Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T124137Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T124147Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T130800Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T125249Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T124915Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T130410Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T130806Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T131020Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T123922Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T124019Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T125403Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T131037Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T123921Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T123920Z.txt
NEON.D16.ABBY.DP1.10098.001.readme.20200817T130740Z.txt
NEON.D16.WREF.DP1.10098.001.readme.20200817T130556Z.txt
NEON.D16.WREF.DP1.10098.001.readme.20200817T124831Z.txt
NEON.D16.WREF.DP1.10098.001.readme.20200928T200507Z.txt
NEON.D16.WREF.DP1.10098.001.readme.20201102T133609Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200817T130222Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200817T125918Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200817T124721Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200817T125612Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200817T125020Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20200928T195532Z.txt
NEON.D17.SJER.DP1.10098.001.readme.20201102T134755Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T123957Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T124539Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T124414Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T124804Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T124453Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20200817T125328Z.txt
NEON.D17.SOAP.DP1.10098.001.readme.20201109T145309Z.txt
NEON.D17.TEAK.DP1.10098.001.readme.20200817T124330Z.txt
NEON.D17.TEAK.DP1.10098.001.readme.20200817T125959Z.txt
NEON.D17.TEAK.DP1.10098.001.readme.20200817T125232Z.txt
NEON.D19.BONA.DP1.10098.001.readme.20200817T125536Z.txt
NEON.D19.BONA.DP1.10098.001.readme.20200817T124436Z.txt
NEON.D19.BONA.DP1.10098.001.readme.20200817T124821Z.txt
NEON.D19.BONA.DP1.10098.001.readme.20200817T125528Z.txt
NEON.D19.BONA.DP1.10098.001.readme.20200817T123948Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T130731Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T124300Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T124904Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T124513Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T130528Z.txt
NEON.D19.DEJU.DP1.10098.001.readme.20200817T131257Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T124435Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T124735Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T123944Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T124434Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T125311Z.txt
NEON.D19.HEAL.DP1.10098.001.readme.20200817T125316Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T125028Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T130950Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T130947Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T130222Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T124440Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T124408Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T130403Z.txt
NEON.D20.PUUM.DP1.10098.001.readme.20200817T124300Z.txt
