# Environmental Justice Index (EJI) Data from the Centers for Disease Control and Prevention (CDC)

[Learn more about the Environmental Justice Index (EJI)](https://www.atsdr.cdc.gov/place-health/php/eji/index.html)


## Dataset Structure

The EJI dataset for 2022 and 2024 is organized by state and includes the following file types:

- **CSV Files**: Detailed environmental data for each state.
- **GDB Files**: Geodatabase files for spatial analysis.

## File Naming Convention

Files are named in the following format:

```
EJI_{Year}_{State}_{FileType}.zip
```

For example:

- `EJI_2022_Alabama_CSV.zip`
- `EJI_2022_Alabama_GDB.zip`


## Directory Structure

```
└── 📁cdc-ej-index
    └── 📁2022
        └── 📁By State
            └── EJI_2022_Alabama_CSV.zip
            └── EJI_2022_Alabama_GDB.zip
            └── EJI_2022_Arizona_CSV.zip
            └── EJI_2022_Arizona_GDB.zip
            └── EJI_2022_Arkansas_CSV.zip
            └── EJI_2022_Arkansas_GDB.zip
            └── EJI_2022_California_CSV.zip
            └── EJI_2022_California_GDB.zip
            └── EJI_2022_Colorado_CSV.zip
            └── EJI_2022_Colorado_GDB.zip
            └── EJI_2022_Connecticut_CSV.zip
            └── EJI_2022_Connecticut_GDB.zip
            └── EJI_2022_Delaware_CSV.zip
            └── EJI_2022_Delaware_GDB.zip
            └── EJI_2022_District_of_Columbia_CSV.zip
            └── EJI_2022_District_of_Columbia_GDB.zip
            └── EJI_2022_Florida_CSV.zip
            └── EJI_2022_Florida_GDB.zip
            └── EJI_2022_Georgia_CSV.zip
            └── EJI_2022_Georgia_GDB.zip
            └── EJI_2022_Idaho_CSV.zip
            └── EJI_2022_Idaho_GDB.zip
            └── EJI_2022_Illinois_CSV.zip
            └── EJI_2022_Illinois_GDB.zip
            └── EJI_2022_Indiana_CSV.zip
            └── EJI_2022_Indiana_GDB.zip
            └── EJI_2022_Iowa_CSV.zip
            └── EJI_2022_Iowa_GDB.zip
            └── EJI_2022_Kansas_CSV.zip
            └── EJI_2022_Kansas_GDB.zip
            └── EJI_2022_Kentucky_CSV.zip
            └── EJI_2022_Kentucky_GDB.zip
            └── EJI_2022_Louisiana_CSV.zip
            └── EJI_2022_Louisiana_GDB.zip
            └── EJI_2022_Maine_CSV.zip
            └── EJI_2022_Maine_GDB.zip
            └── EJI_2022_Maryland_CSV.zip
            └── EJI_2022_Maryland_GDB.zip
            └── EJI_2022_Massachusetts_CSV.zip
            └── EJI_2022_Massachusetts_GDB.zip
            └── EJI_2022_Michigan_CSV.zip
            └── EJI_2022_Michigan_GDB.zip
            └── EJI_2022_Minnesota_CSV.zip
            └── EJI_2022_Minnesota_GDB.zip
            └── EJI_2022_Mississippi_CSV.zip
            └── EJI_2022_Mississippi_GDB.zip
            └── EJI_2022_Missouri_CSV.zip
            └── EJI_2022_Missouri_GDB.zip
            └── EJI_2022_Montana_CSV.zip
            └── EJI_2022_Montana_GDB.zip
            └── EJI_2022_Nebraska_CSV.zip
            └── EJI_2022_Nebraska_GDB.zip
            └── EJI_2022_Nevada_CSV.zip
            └── EJI_2022_Nevada_GDB.zip
            └── EJI_2022_New_Hampshire_CSV.zip
            └── EJI_2022_New_Hampshire_GDB.zip
            └── EJI_2022_New_Jersey_CSV.zip
            └── EJI_2022_New_Jersey_GDB.zip
            └── EJI_2022_New_Mexico_CSV.zip
            └── EJI_2022_New_Mexico_GDB.zip
            └── EJI_2022_New_York_CSV.zip
            └── EJI_2022_New_York_GDB.zip
            └── EJI_2022_North_Carolina_CSV.zip
            └── EJI_2022_North_Carolina_GDB.zip
            └── EJI_2022_North_Dakota_CSV.zip
            └── EJI_2022_North_Dakota_GDB.zip
            └── EJI_2022_Ohio_CSV.zip
            └── EJI_2022_Ohio_GDB.zip
            └── EJI_2022_Oklahoma_CSV.zip
            └── EJI_2022_Oklahoma_GDB.zip
            └── EJI_2022_Oregon_CSV.zip
            └── EJI_2022_Oregon_GDB.zip
            └── EJI_2022_Pennsylvania_CSV.zip
            └── EJI_2022_Pennsylvania_GDB.zip
            └── EJI_2022_Rhode_Island_CSV.zip
            └── EJI_2022_Rhode_Island_GDB.zip
            └── EJI_2022_South_Carolina_CSV.zip
            └── EJI_2022_South_Carolina_GDB.zip
            └── EJI_2022_South_Dakota_CSV.zip
            └── EJI_2022_South_Dakota_GDB.zip
            └── EJI_2022_Tennessee_CSV.zip
            └── EJI_2022_Tennessee_GDB.zip
            └── EJI_2022_Texas_CSV.zip
            └── EJI_2022_Texas_GDB.zip
            └── EJI_2022_Utah_CSV.zip
            └── EJI_2022_Utah_GDB.zip
            └── EJI_2022_Vermont_CSV.zip
            └── EJI_2022_Vermont_GDB.zip
            └── EJI_2022_Virginia_CSV.zip
            └── EJI_2022_Virginia_GDB.zip
            └── EJI_2022_Washington_CSV.zip
            └── EJI_2022_Washington_GDB.zip
            └── EJI_2022_West_Virginia_CSV.zip
            └── EJI_2022_West_Virginia_GDB.zip
            └── EJI_2022_Wisconsin_CSV.zip
            └── EJI_2022_Wisconsin_GDB.zip
            └── EJI_2022_Wyoming_CSV.zip
            └── EJI_2022_Wyoming_GDB.zip
        └── EJI_2022_Data_Dictionary_508.pdf
        └── EJI_2022_United_States_CSV.zip
        └── EJI_2022_United_States_GDB.zip
    └── 📁2024
        └── 📁By State
            └── EJI_2024_Alabama_CSV.zip
            └── EJI_2024_Alabama_GDB.zip
            └── EJI_2024_Arizona_CSV.zip
            └── EJI_2024_Arizona_GDB.zip
            └── EJI_2024_Arkansas_CSV.zip
            └── EJI_2024_Arkansas_GDB.zip
            └── EJI_2024_California_CSV.zip
            └── EJI_2024_California_GDB.zip
            └── EJI_2024_Colorado_CSV.zip
            └── EJI_2024_Colorado_GDB.zip
            └── EJI_2024_Connecticut_CSV.zip
            └── EJI_2024_Connecticut_GDB.zip
            └── EJI_2024_Delaware_CSV.zip
            └── EJI_2024_Delaware_GDB.zip
            └── EJI_2024_District_of_Columbia_CSV.zip
            └── EJI_2024_District_of_Columbia_GDB.zip
            └── EJI_2024_Florida_CSV.zip
            └── EJI_2024_Florida_GDB.zip
            └── EJI_2024_Georgia_CSV.zip
            └── EJI_2024_Georgia_GDB.zip
            └── EJI_2024_Idaho_CSV.zip
            └── EJI_2024_Idaho_GDB.zip
            └── EJI_2024_Illinois_CSV.zip
            └── EJI_2024_Illinois_GDB.zip
            └── EJI_2024_Indiana_CSV.zip
            └── EJI_2024_Indiana_GDB.zip
            └── EJI_2024_Iowa_CSV.zip
            └── EJI_2024_Iowa_GDB.zip
            └── EJI_2024_Kansas_CSV.zip
            └── EJI_2024_Kansas_GDB.zip
            └── EJI_2024_Kentucky_CSV.zip
            └── EJI_2024_Kentucky_GDB.zip
            └── EJI_2024_Louisiana_CSV.zip
            └── EJI_2024_Louisiana_GDB.zip
            └── EJI_2024_Maine_CSV.zip
            └── EJI_2024_Maine_GDB.zip
            └── EJI_2024_Maryland_CSV.zip
            └── EJI_2024_Maryland_GDB.zip
            └── EJI_2024_Massachusetts_CSV.zip
            └── EJI_2024_Massachusetts_GDB.zip
            └── EJI_2024_Michigan_CSV.zip
            └── EJI_2024_Michigan_GDB.zip
            └── EJI_2024_Minnesota_CSV.zip
            └── EJI_2024_Minnesota_GDB.zip
            └── EJI_2024_Mississippi_CSV.zip
            └── EJI_2024_Mississippi_GDB.zip
            └── EJI_2024_Missouri_CSV.zip
            └── EJI_2024_Missouri_GDB.zip
            └── EJI_2024_Montana_CSV.zip
            └── EJI_2024_Montana_GDB.zip
            └── EJI_2024_Nebraska_CSV.zip
            └── EJI_2024_Nebraska_GDB.zip
            └── EJI_2024_Nevada_CSV.zip
            └── EJI_2024_Nevada_GDB.zip
            └── EJI_2024_New_Hampshire_CSV.zip
            └── EJI_2024_New_Hampshire_GDB.zip
            └── EJI_2024_New_Jersey_CSV.zip
            └── EJI_2024_New_Jersey_GDB.zip
            └── EJI_2024_New_Mexico_CSV.zip
            └── EJI_2024_New_Mexico_GDB.zip
            └── EJI_2024_New_York_CSV.zip
            └── EJI_2024_New_York_GDB.zip
            └── EJI_2024_North_Carolina_CSV.zip
            └── EJI_2024_North_Carolina_GDB.zip
            └── EJI_2024_North_Dakota_CSV.zip
            └── EJI_2024_North_Dakota_GDB.zip
            └── EJI_2024_Ohio_CSV.zip
            └── EJI_2024_Ohio_GDB.zip
            └── EJI_2024_Oklahoma_CSV.zip
            └── EJI_2024_Oklahoma_GDB.zip
            └── EJI_2024_Oregon_CSV.zip
            └── EJI_2024_Oregon_GDB.zip
            └── EJI_2024_Pennsylvania_CSV.zip
            └── EJI_2024_Pennsylvania_GDB.zip
            └── EJI_2024_Rhode_Island_CSV.zip
            └── EJI_2024_Rhode_Island_GDB.zip
            └── EJI_2024_South_Carolina_CSV.zip
            └── EJI_2024_South_Carolina_GDB.zip
            └── EJI_2024_South_Dakota_CSV.zip
            └── EJI_2024_South_Dakota_GDB.zip
            └── EJI_2024_Tennessee_CSV.zip
            └── EJI_2024_Tennessee_GDB.zip
            └── EJI_2024_Texas_CSV.zip
            └── EJI_2024_Texas_GDB.zip
            └── EJI_2024_Utah_CSV.zip
            └── EJI_2024_Utah_GDB.zip
            └── EJI_2024_Vermont_CSV.zip
            └── EJI_2024_Vermont_GDB.zip
            └── EJI_2024_Virginia_CSV.zip
            └── EJI_2024_Virginia_GDB.zip
            └── EJI_2024_Washington_CSV.zip
            └── EJI_2024_Washington_GDB.zip
            └── EJI_2024_West_Virginia_CSV.zip
            └── EJI_2024_West_Virginia_GDB.zip
            └── EJI_2024_Wisconsin_CSV.zip
            └── EJI_2024_Wisconsin_GDB.zip
            └── EJI_2024_Wyoming_CSV.zip
            └── EJI_2024_Wyoming_GDB.zip
        └── EJI_2024_United_States_CSV.zip
        └── EJI_2024_United_States_GDB.zip
        └── Note: 2024 Data Dictionary Not Found
    └── .gitignore
    └── LICENSE
    └── README.md
```


### Notes

**Issues**

Please report issues to the [issues page](https://github.com/abhatia08/cdc-eji-data/issues).

**Disclaimer**

The data are provided in the same format as provided by the CDC at the time of download, without any modifications. I cannot guarantee its completeness or accuracy.
This data may eventually be moved to a more formal data repository, and is only temporarily hosted here.