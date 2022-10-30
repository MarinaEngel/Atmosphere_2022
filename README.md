A description for suplementary materials. 
Main results are shown in the article 
Tarasenkov M.V., Engel M.V., Zonov M.N., Belov V.V. "Assessing the cloud adjacency 
effect on retrieval of the ground surface reflectance from MODIS satellite data for 
the Baikal area" // Atmosphere.

Folder include file "results.txt" and folder "CAE masks". 
File "results.txt" contains the following information: 1) date and time; 2) scene; 3)  MODIS channel; 4) channel range; 5) aerosol optical 
depth; 6) solar zenith angle, deg; 7) receiver zenith angle, deg; 8) cloud geometrical 
thickness, km; 9) cloud index; 10) cloud extintion, km-1; 11) ground surface 
reflectance; 12) cloud optical thichness; 13) Cloud Adjacency Effect (CAO) radius R* , km.

Example:
01.07.2021 4:15	1	8	0.405 mkm 0.420 mkm	0.432	30.0	6.3	3.64	
0.406	6.41	0.375	23.32	21.9
01.07.2021 4:15 - date and time; 
1 - scene; 
8 -  MODIS channel; 
0.405 mkm 0.420 mkm - channel range;
0.432 - aerosol optical depdt; 
30.0 - solar zenith angle, deg; 
6.3 - receiver zenith angle, deg;
3.64 - cloud geometrical thickness, km;
0.406 - cloud index;
6.41 - cloud extintion, km-1;
0.375 - ground surface reflectance;
23.32 - cloud optical thickness;
21.9 - Cloud Adjacency Effect (CAO) radius R* , km.
Folder "CAE masks" contains the Cloud Adjacency Effect masks for MODIS channels 2 
(0.841 mkm - 0.876 mkm) and 4 (0.545 mkm - 0.565 mkm). Names of files correspond to 
date,time and number of MODIS channel. For example, file with name 
"mod1830500_ch2.bmp" corresponds to the cloud adjacency effect mask for the MODIS 
channel 2 (0.841 mkm - 0.876 mkm), 183-th day of the 2021 year and time 05:00 UTC.
In the figures black points correcpond to cloud pixels, red points correcpond to 
pixels with high influence of cloud adjacency effect and blue pixels correcpond to 
pixels with low cloud adjacency effect. 

Contacts: principal investigator Mikhail Tarasenkov, e-mail tmv@iao.ru. 
Organization: V.E. Zuev Institute of Atmospheric Optics SB RAS (IAO SB RAS) Postal Address: 1, Academician Zuev square Tomsk 634055 Russia
