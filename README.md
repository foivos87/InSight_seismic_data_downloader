# InSight_seismic_data
Scripts for InSight seismic data download and processing.

-- Dependencies --

In order to use this suite, a python3 installation in your system is necessary, as well as the ObsPy open sourced framework (https://github.com/obspy/obspy/wiki). Please acknowledge and cite the ObsPy references accordingly.

-- Contents --

This repository contains:

1. The 6th version of the Marsquakes Catalog. Citation: InSight Marsquake Service (2021). Use the link for the download and cite accordingly.
2. The python script **make_seismic_catalog.py** that creates the text file of the catalog, needed for the event data downloaders.
3. The python script **eventdownloader.py**, which is used for downloading and processing of a unique event data.
4. The python script **massivedownloader.py**, which is used for downloading and processing of events' data of a specific event Type and Quality (see Clinton et al., 2021 for details).

-- References --

1. Clinton, J. F., Ceylan, S., van Driel, M., Giardini, D., Stähler, S. C., Böse, M., … Stott, A. E. (2021). The Marsquake catalogue from InSight, sols 0–478. Physics of the Earth and Planetary Interiors, 310, 106595. doi:10.1016/j.pepi.2020.106595
2. InSight Marsquake Service (2021). Mars Seismic Catalogue, InSight Mission; V6 2021-04-01. ETHZ, IPGP, JPL, ICL, MPS, Univ. Bristol. https://doi.org/10.12686/a11
3. 
