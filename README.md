## ESM 267 Assignment 3

Courtney Schatzman
Link to live site: https://cschatzm.github.io/ESM267_Assignment3/

# California State Timber Harvest Planning Regions Since 2010 Compared with Government Agency Controlled Lands

The Timber Harvest Plan (THP) regions are seen in red. They are representative of privately held timber lands primarily in Northern Ca. The federal, state, local, NGO, and tribal lands are in yellow, light green, kelly green, aqua, and blue respectively. 

The framing of our project within the Californian privately-owned timberlands requires an understanding of this industry’s history within the state. In the following section, pressures experienced by the industry for both public and private land are expanded. Media has highlighted opportunities and frustrations and has even suggested solutions to wildfire risks and hazards linked with California’s timber industry. We hope to delineate the differences faced by private and public timberlands, along with the importance of developing solutions specific to each. Our project is applicable specifically to timber actions on privately-owned timberlands.

California today holds over 33 million acres of forest and is dispersed among federal, state, local, and NGO agencies along with Native American tribes, private corporations, and individuals (https://ucanr.edu/sites/forestry/California_forests/). Linked with the diversity in ownership is the variety in management practices. 

Thirty percent (30%) of the forested land is considered timberland - “forests that can be managed for sustainable production of wood products”. Of this, 1.65 million hectares is private timberland and 2.55 million hectares is National Forest. While some forest land is simply not productive enough to be utilized for timber growth, there is also a portion that is designated to be preserved as a forest. (https://ucanr.edu/sites/forestry/files/248435.pdf, https://www.fs.fed.us/pnw/pubs/pnw_gtr908.pdf) 

## Methods 

1) Map was assembled, symbolized, and completed in QGIS.

2) The map was then exported using qgis2web and leaflet.
  - Issues: QGIS crashed when using qgis2web interface with the complete THP harvest dataset. 
    The dataset had to to be desimated to 2010-present from the original historical range.

3) The map was imbedded using iframe. 

4) The assignment #3 was submitted via github url.

### Data References

1) Data was collected from CALFIRE & BIOS:
- ownership18_2.gdb (agency gdb)
- Cnty18_2 (county gdb)
- Title Timber Harvest Plan Boundaries - Statewide [ds816]
- Publication date 2018-04-0800:00:00
- ftp://ftp.fire.ca.gov/forest/Statewide_Timber_Harvest/
