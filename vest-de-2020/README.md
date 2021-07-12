# vest-de-2020

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-delaware-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST DE 2020 file
   - Date accessed: 6/29/2021
   - Link:https://dataverse.harvard.edu/file.xhtml?fileId=4773531&version=12.0
   - File: `de_2020.zip`
- File: VEST documentation file, 2020
   - Date accessed: 6/29/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4773529&version=9.0
   - File: `documentation.txt`
- File: Precinct-level shapefile used by VEST
  - Date accessed: 7/1/2021
  - Link: https://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries/explore?location=39.144386%2C-75.386594%2C9.23
  - Note: selected 'Download', 'Shapefile', 'Download available data'. 

### Inaccessible files:
- File: Precinct Level Election results, 2020
  - Date accessed: 7/1/2021
  - Link: https://elections.delaware.gov/results/html/index.shtml?electionId=GE2020#electionReport3
  - File: `2020_GeneralElection_Results_ByElectionDistrict.xlsx`
  - Note: The 'Download CVS Report' does not have Election Districts. Called the DE Department of Elections (302-739-4277) on 7/1/2021. Spoke to Catherine Sheehan who agreed that there is no precinct-level election results file on their website. She directed us to submit a FOIA request for the precinct-level data, and said it could take a few weeks for that. Received a call back later on 7/1/2021 and told that they have the file and will email it to us on 7/2/2021. Received the file on 7/2/2021. 

## File processing:

`vest-de-2020-validation.ipynb` is the script that is the basis of the validation report
