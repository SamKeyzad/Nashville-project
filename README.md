# Nashville-project
The Nashville Housing project focuses on data cleaning and normalization procedures for a dataset containing housing information. This project involves tasks such as handling null values, identifying and resolving data redundancies, and normalizing address information. 
The Nashville Housing project tackles data management challenges within a housing dataset, emphasizing data cleanliness and organization. By employing SQL queries, the project addresses various aspects of data quality assurance and normalization.

Initially, the dataset undergoes thorough cleaning procedures. Null values are handled across multiple columns using conditional statements (CASE statements), ensuring data integrity. Redundancies within the dataset, particularly in the ParcelID and PropertyAddress fields, are identified and resolved through self-joins and conditional updates. These steps mitigate inconsistencies and enhance the dataset's reliability.

Moreover, the project focuses on normalizing address information to facilitate easier analysis and interpretation. Techniques such as substring extraction and string manipulation functions are applied to break down PropertyAddress and OwnerAddress fields into separate components like street address, city, and state. This normalization process enhances the dataset's usability and enables more efficient querying and reporting.

A significant aspect of the project involves standardizing categorical data. For instance, values in the SoldAsVacant column are transformed from 'Y' and 'N' to 'Yes' and 'No,' respectively. This standardization improves data clarity and consistency, making it easier to interpret and analyze.

Furthermore, duplicate entries are addressed to ensure data uniqueness. Utilizing Common Table Expressions (CTEs) and window functions, duplicates are identified based on specific criteria like ParcelID, PropertyAddress, SalePrice, SaleDate, and LegalReference. Duplicate records are then systematically removed, optimizing the dataset's integrity and reducing redundancy.

As part of data normalization efforts, redundant columns that violate normalization rules are removed from the dataset. This step streamlines the dataset's structure and conforms to best practices in database design.

Overall, the Nashville Housing project exemplifies the importance of data quality management in real-world datasets. Through meticulous cleaning, normalization, and standardization processes, the project ensures that the housing dataset is accurate, consistent, and well-structured. These efforts lay a solid foundation for subsequent data analysis, modeling, and decision-making processes, ultimately enhancing insights into Nashville's housing market.
