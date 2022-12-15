# Census-API-data-collection
## This is collecting the 15 CDC social vulnerability Index factors from Census API from 2010 to 2020 with adding 4 age groups by using data scraping technology.
## The detailed description of Census variables can be found: https://github.com/azh2/Social-Vulnerability-R and https://api.census.gov/data.html  
## The list of the 15 CDC Social Vulnerability Index factors are as follow:
### Socail Vulnerability Index Factors:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/svi1.png" alt="step" title="step">

### The main function is created to request data from Census API:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/svi2.png" alt="step" title="step">

### Factor 1. per capita income: B19301_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor1.png" alt="factor" title="factor">

### Factor 2. Percent of Population Below Poverty Level: (C17002_002E+C17002_003E)/C17002_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor2.png" alt="factor" title="factor">

### Factor 3.Percent of Population 25+ with Less than a 12th Grade Education: (B15002_003E,B15002_004E,B15002_005E,B15002_003E,B15002_006E,B15002_007E,B15002_008E,B15002_009E,B15002_010E,B15002_020E,B15002_021E,B15002_022E,B15002_023E,B15002_024E,B15002_025E,B15002_026E,B15002_027E)/B15003_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor3_1.png" alt="factor" title="factor">
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor3_2.png" alt="factor" title="factor">

### Factor 4. Percent of Population Living in Mobile Homes: (B25033_006E+B25033_007E+B25033_012E+B25033_013E)/B25033_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor4.png" alt="factor" title="factor">

### Factor 5. Percent of Population with No Vehicle Available: (B25044_003E+B25044_010E)/B25044_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor5.png" alt="factor" title="factor">

### Factor 6. Percent of Population Unemployed:sum(B21005_006E, B21005_007E, B21005_011E,B21005_012E,B21005_017E,B21005_022E,B21005_028E,B21005_029E,B21005_033E,B21005_034E)/B21005_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor6.png" alt="factor" title="factor">

### Factor 7. Percent of Population Living In Accommodations with Less Than 1 Room Per Person/Crowding: (B25014_005E+B25014_006E+B25014_007E+B25014_011E+B25014_012E+B25014_013E)/B25014_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor7.png" alt="factor" title="factor">

### Factor 8. Percent of Housing Units with 10+ Units in Structure: (B25024_007E+B25024_008E+B25024_009E)/B25024_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor8.png" alt="factor" title="factor">

### Factor 9. Percent Of Population 65+: (B01001_020E,B01001_021E,B01001_022E,B01001_023E,B01001_024E,B01001_025E,B01001_044E,B01001_045E,B01001_046E,B01001_047E,B01001_049E)/B01001_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor9.png" alt="factor" title="factor">

### Factor 10. Percent Of Population Who Do Not Speak English: B99163_005E/B99163_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor10.png" alt="factor" title="factor">

### Factor 11. Percent of Population 17 Years of Age and Under: (B01001_003E+B01001_004E+B01001_005E+B01001_006E+B01001_027E+B01001_028E+B01001_029E+B01001_030E)/B01003_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor11.png" alt="factor" title="factor">

### Factor 12. Percent Minority: 1-(B03002_003E/B03002_001E):
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor12.png" alt="factor" title="factor">

### Factor 13. Percent of Population with a Disability: (B18101_004E+B18101_007E+B18101_010E+B18101_013E+B18101_016E+B18101_019E)/B18101_002E + (B18101_023E+B18101_026E+B18101_029E+B18101_032E+B18101_035E+B18101_038E)/B18101_021E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor13.png" alt="factor" title="factor">

### Factor 14. Percent of Population Living in Group Quarters: B26001_001E/B01003_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor14.png" alt="factor" title="factor">

### Factor 15. Percent of Children Living in Single Parent Households: (B09008_010E+B09008_011E+B09008_012E)/B09008_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor15.png" alt="factor" title="factor">

### Factor 16. age 18 to 34 (B01001_007E+B01001_008E+B01001_009E+B01001_010E+B01001_011E+B01001_012E+B01001_031E+B01001_032E+B01001_033E+B01001_034E+B01001_035E+B01001_036E)/B01001_001E :
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor16.png" alt="factor" title="factor">

### Factor 17. Age 35 to 44 (B01001_013E+B01001_014E+B01001_037E+B01001_038E)/B01001_001E
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor17.png" alt="factor" title="factor">

### Factor 18.age 45 to 54 (B01001_015E+B01001_016E+B01001_039E+B01001_040E)/B01001_001E :
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor18.png" alt="factor" title="factor">

### Factor 19. age 55 to 64 (B01001_017E+B01001_018E+B01001_019E+B01001_041E+B01001_042E+B01001_043E)/B01001_001E:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor19.png" alt="factor" title="factor">

### Combine the 19 factors together:
<img src="https://github.com/Wenhuan2516/Census-API-data-collection/blob/main/factor20.png" alt="factor" title="factor">

