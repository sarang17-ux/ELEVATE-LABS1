Loaded the raw Netflix dataset using Pandas.

Identified missing values using isnull().

Removed duplicate records using drop_duplicates().

Filled missing values in director, cast, country, and rating with "Unknown".

Filled missing date_added and duration using the most frequent value.

Removed rows where the title was missing.

Standardized text columns by removing extra spaces and converting them to title case.

Renamed column headers to lowercase with underscores.
