# vest-de-2018

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-delaware-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST DE 2018 file
   - Date accessed: 6/29/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/XM4ZGG&version=41.0
   - File: `de_2018.zip`
- File: VEST documentation file, 2018
   - Date accessed: 6/29/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4863187&version=41.0
   - File: `documentation.txt`
- File: Precinct-level shapefile used by VEST
  - Date accessed: 7/1/2021
  - Link: https://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries/explore?location=39.144386%2C-75.386594%2C9.23
  - Note: selected 'Download', 'Shapefile', 'Download available data'. It is not clear if this is reflective of the precincts in 2018. 
- File: Precinct Level Election results, 2018
  - Date accessed: 7/9/2021
  - Link: https://elections.delaware.gov/archive/elect18/elect18_general/html/stwres.shtml
  
## File processing:

`vest-de-2018-validation.ipynb` is the script that is the basis of the validation report
