#  Data clean, Data Manipulation after Import Raw Data 
Before I manipulated data into meaningful insight, I first cleaned the original raw data.  The data cleaning process involves inspecting the dataset for structure, handling missing values, checking and removing duplicates and outliers, removing special characters, formatting standardization, transforming data, feature engineering, and conducting final validation for quality assurance.  Here are some sample data cleaning:

### 1. Handling Missing Values:
Identifying and filling in missing data points using appropriate methods. 
I replaced null values with Data Not Available.

![c1](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/4ddfdac3-945e-423e-b382-cd3a7b1d77cf)

#

### 2. Removing Special Character:
Identifying and removing special characters or rows from the dataset. 

![c2](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/6aab2a02-8189-47e3-893b-f034f35d735b)

#

### 3. Format Standardization:
Ensuring consistent formats for dates, numbers, and other data types.
As a result, Wii Sports retains its position as the number one global sale, followed by Grand Theft Auto V. The latter's high ranking is primarily attributed to its availability on five different platforms.
I standardized the User_Score field format by removing "tbd" and converted the field to numeric.

![s4](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/5232d0de-ddb4-4c7d-96be-74b15022c7ad)

#

### 4. Removing Duplicates:
Identifying and removing duplicate records or rows from the dataset. 
I did not find any duplicate records, but I observed duplicate game names due to the data being listed by both game name and platform. 
Consequently, I opted to create a reference table based on game names. I established a game name reference table to map and generate an additional view.

As a result, "Grand Theft Auto V" holds a global sales rank of #2, with specific rankings for different platforms: #17 for PS3, #24 for X360, #43 for PS4, #179 for XOne, and #1,723 for PC.

![s8](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/43c5409d-4e74-4d88-a5b9-84d5b8944f09)


#

### 5. Transforming Data:
Converting data into scales.  I grouped the game year release field by decade and created a new category field.

![s5](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/a09fccd7-e5e0-404a-bde5-d4d22f7e41af)

#
Here's another example: I transformed the critic score by dividing it by 2 and then by 100 to obtain a critic score star, akin to online product ratings. I applied a similar concept to the user score.

![s7](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/58b458d0-8bc4-4d1e-af04-0191f542077d)


#
I've established a field to measure the global sales rank, but this data is specific to "game and platform". 
To view the global sales rank by game, I intend to enhance the measurement further by creating a game name reference table that will allow for mapping and aggregating the data based on the game names.

![s6](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/389d99f0-b11b-49d9-8916-0ef19d505260)

#### Lesson Learned: 
The issue of data misrepresentation has been addressed through rigorous data cleaning, manipulation, and mapping processes. 
By creating a game name reference table, we ensure a more accurate representation of the top global sales, considering both the game name and the number of platforms. 
This approach aims to provide a clearer and unbiased view of the data, mitigating potential misinterpretations that could arise from the original raw data structure.
