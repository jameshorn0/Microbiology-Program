# Microbiology-Program
A program to format data output from a plate reader.

This program takes the data exported from a plate reader and formats it based upon the information in the plate layout document. 
The examples are from a 96-well plate experiment that took readings every 15 minutes for 48 hours (final dimensions: 96 x 192).

Once data is formatted and grouped accordingly, the script will generate mean values for grouped conditions.

The script will then produce and save graphs plotting aggregate and control values as well as individual columns for comparion.

Finally, the script will save the following:
    - all individual graphs (aggregates and individual samples)
    - original data as well as aggregated data in a new excel workbook
    - a powerpoint containing all graphs
