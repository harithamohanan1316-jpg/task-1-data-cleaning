Duplicates: Removed XX duplicate rows using the 'Remove Duplicates' feature.
Missing Values: Handled nulls by [dropping rows/imputing with median] in columns [list columns].
Text Standardization: Standardized [Customer Name, City, State] columns using =LOWER(TRIM()) to ensure consistency in case and spacing.
Date/Type Conversion: Converted Order Date and Ship Date to a standard date format (YYYY-MM-DD). Confirmed all numerical fields are formatted as Number/General.
