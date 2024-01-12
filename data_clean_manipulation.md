#  Data clean, Data Manipulation after Import Raw Data 

### 1. Handling Missing Values:
Identifying and filling in missing data points using appropriate methods. 
I replaced null values with Data Not Available.

![c1](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/8d76d52d-e803-460d-83fd-aa0249c2569b)

#

### 2. Removing Duplicates:
Identifying and removing duplicate records or rows from the dataset. 
I did not find any duplicate records, but I observed duplicate game names due to the data being listed by both game name and platform. 
Consequently, I opted to create a reference table based on game names. I established a game name reference table to map and generate an additional view.

![c2](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/0a0a9c5f-ef1a-4400-9f48-208d37cdc3ed)


#

### 3. Format Standardization:
Ensuring consistent formats for dates, numbers, and other data types.
As a result, Wii Sports retains its position as the number one global sale, followed by Grand Theft Auto V. The latter's high ranking is primarily attributed to its availability on five different platforms.
I standardized the User_Score field format by removing "tbd" and converted the field to numeric.

![c3](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/e899ba8e-db5b-4bc3-8c1f-90b76a6b847e)

#

### 4. Transforming Data:
Converting data into scales.  I grouped the game year release field by decade and created a new category field.

![c4](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/16654537-1897-4999-a6ab-95c59e077542)

#
Here's another example: I transformed the critic score by dividing it by 2 and then by 100 to obtain a critic score star, akin to online product ratings. I applied a similar concept to the user score.

![c5](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/8cd78ad7-e9df-495a-86da-7837dcc8e253)

#
I've established a field to measure the global sales rank, but this data is specific to "game and platform". 
To view the global sales rank by game, I intend to enhance the measurement further by creating a game name reference table that will allow for mapping and aggregating the data based on the game names.

![c7](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/30e1e661-63b9-49e3-8a48-df53011f00e3)


#### Lesson Learned: 
The issue of data misrepresentation has been addressed through rigorous data cleaning, manipulation, and mapping processes. 
By creating a game name reference table, we ensure a more accurate representation of the top global sales, considering both the game name and the number of platforms. 
This approach aims to provide a clearer and unbiased view of the data, mitigating potential misinterpretations that could arise from the original raw data structure.
