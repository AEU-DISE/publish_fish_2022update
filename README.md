# publish_fish_2022update
Code for publishing YBFMP fish data to EDI that was adapted to add more data for use in the YBFMP Hitch presentation for IEP 2023

## Notes on folders and process
The actual processing of data and code was done in the main publish_fish folder, using the .Rmd files. Once the raw data from data_raw were cleaned in clean_fish_tables, the data were written to data_clean. These files were read into integrate_fish_data to create the integrated dataset. 
