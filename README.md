thai-election-2023 (IN PROGRESS)
=============
Starting from GeoJSON files (created by Apisit Toompakdee) that defines Thailand's provinces, I plan to add election results from the 2023 general election on May 14, 2023. The primary goal is to create a map that visualizes vote shares of the following political parties:
* พรรคก้าวไกล Move Forward Party (MF)
* พรรคเพื่อไทย Pheu Thai Party (PT)
* พรรคภูมิใจไทย Bhumjaithai Party (BJT)
* พรรครวมไทยสร้างชาติ United Thai Nation Party (UTN)
* พรรคพลังประชารัฐ Palang Pracharath Party (PP)
* พรรคประชาธิปัตย์ Democrat Party (DEM)

# Data Collection
I haven't been able to find downloadable election data by district, so I may end up creating one manually.

# Motivation
While most election maps on the media show colors of the winning parties in each district, such maps do not provide a full picture. For example, regardless of whether Party A won 80% or 50% of the votes in a district, that district will be colored with Party A's color.

It could be interesting to visualize the election results by percentage vote shares (color scale from white to dark corresponding to 0->100%). This would allow us to see, for example, how many and which provinces Party A won by landslide vs provinces where Party A won much fewer votes. We can see how much (or how little) these results correlate with the provinces' populations, GDP, etc.
