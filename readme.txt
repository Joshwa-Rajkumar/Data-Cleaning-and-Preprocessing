Tast 1: Data Cleaning and Preprocessing

1. Downloaded Netflix Movies and TV Shows till 2025 dataset from Kaggle (obtained 2 csv files)
2. Combine two files into one by copying one table to another (could be helpful, If I had Power Query)
3. Dropped unwanted columns (like full story as a column "Description", and full castings as a "Cast")
4. found Duplicates from dataset by applying conditional formatting in Excel (later came to know some films had same name, even same year)
5. Create a helper column to find real duplicates by combining Title + Director + Year + Language (we can easily do "Remove duplicates", but I tried the harder way to explore)
6. after detecting no duplicates, converted date formats to a consistent type i.e., dd-mm-yyyy
7. Formatting columns like budget and revenue as Accounting for calculations (if any)
8. Struggled to convert UTF-8 format (almost took me half a day, still couldn't convert, maybe I should've tried delimited before merging the two files)
9. Handled missing values by filling "Unknown, n/a" for text columns, 0 for number columns
