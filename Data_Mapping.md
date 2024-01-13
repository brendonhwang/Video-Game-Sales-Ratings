# Data Analysis after Data clean, Data Manipulate, Mapping 

### Original Raw Data and Data Output
The raw data in the "video_game" dataset includes sales information categorized by game name and platform. 
The analysis reveals that the top global sales are led by Wii Sports, followed by Super Mario Bros, Mario Kart Wii, Wii Sports Resort, and Pokemon Red/Pokemon Blue.


![1](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/5c384b06-792a-4950-a7bb-b0f3910745bc)

#

### Data Issue (misrepresentative data output)
The raw data includes global sales by both game name and platform. To avoid confusion and accurately identify the top five global sales, I created a game name reference table. 
This table helps retrieve data specifically for the top five global sales by name, ensuring clarity for those interested in overall top game sales.  Below are the sample data (see Grand Theft Auto V has five platforms)


![2](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/d4d43d53-b083-46b2-8ee9-edef8fb64153)

#

### Manipulated Data that results in meaningful insight
To provide more accurate information regarding the top game sales irrespective of platforms, I created a game name reference table. Using this reference table, I was able to retrieve data for the top five global sales, including the game name, global sales, and the number of platforms the game is available on.  

As a result, Wii Sports retains its position as the number one global sale, followed by Grand Theft Auto V. The latter's high ranking is primarily attributed to its availability on five different platforms.

![3](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/73046c7d-e879-4946-b8ef-804d5eb4ec86)


#### Lesson Learned: 
The issue of data misrepresentation has been addressed through rigorous data cleaning, manipulation, and mapping processes. 
By creating a game name reference table, we ensure a more accurate representation of the top global sales, considering both the game name and the number of platforms. 
This approach aims to provide a clearer and unbiased view of the data, mitigating potential misinterpretations that could arise from the original raw data structure.

#### Scripts for analysis

![4](https://github.com/brendonhwang/Video-Game-Sales-Ratings/assets/155376651/64c70934-75be-42f8-a027-37eaf56e4dc3)