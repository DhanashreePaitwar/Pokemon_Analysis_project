# Pokemon_Analysis_project
# Libraries used in project :

Pandas : a software library written for the Python programming language for data manipulation and analysis
Numpy : a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
Matplotlib : a plotting library for the Python programming language and its numerical mathematics extension NumPy.
Seaborn : a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

# content
The dataset contains list of the 890 known Pokemons until the 8th Generation and his varities.

# Acknowledgement

Dataset is available on kaggle : https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420
The information found in below websites
- https://pokemondb.net/ (mostly everything)
- https://www.serebii.net/ (information about sub-legendary, legendary and mythical pokemon)

# About the Dataset

The dataset contains information about 890 Pokemons(1028 including varities). It Contains 1028 Rows and 53 columns.
The information stored in diffrent groups.

# Pokemon Data:
* pokedex_number: The entry number of the Pokemon in the National Pokedex    
* name: The English name of the Pokemon            
* german_name: The German name of the Pokemon               
* japanese_name: The Original Japanese name of the Pokemon     
* generation: The numbered generation which the Pokemon was first introduced
* issublegendary: Denotes if the Pokemon is sub-legendary
* is_legendary: Denotes if the Pokemon is legendary
* is_mythical: Denotes if the Pokemon is mythical
* species: The Categorie of the Pokemon
* type_number: Number of types that the Pokemon has
* type_1: The Primary Type of the Pokemon
* type_2: The Secondary Type of the Pokemon if it has it
* height_m: Height of the Pokemon in meters
* weight_kg: The Weight of the Pokemon in kilograms
* abilities_number: The number of abilities of the Pokemon
* ability_?: Name of the Pokemon abilities
* ability_hidden: Name of the hidden ability of the Pokemon if it has one
# Base stats:
* total_points: Total number of Base Points
* hp: The Base HP of the Pokemon
* attack: The Base Attack of the Pokemon
* defense: The Base Defense of the Pokemon
* sp_attack: The Base Special Attack of the Pokemon
* sp_defense: The Base Special Defense of the Pokemon
* speed: The Base Speed of the Pokemon
# Training:
* catch_rate: Catch Rate of the Pokemon
* base_friendship: The Base Friendship of the Pokemon
* base_experience: The Base experience of a wild Pokemon when caught
* growth_rate: The Growth Rate of the Pokemon
# Breeding:
* eggtypenumber: Number of groups where a Pokemon can hatch
* eggtype?: Names of the egg groups where a Pokemon can hatch
* percentage_male: The percentage of the species that are male. Blank if the Pokemon is genderless.
* egg_cycles: The number of cycles (255-257 steps) required to hatch an egg of the Pokemon
# Type defenses:
against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type
Index

In this project I have try to do in depth analysis on Pokemon dataset and to find the patterns and meaningful instights from it.

# Table of content
# 1. Reading dataset
Steps to read the Pokemon dataset.
# 2. Data pepration
In all data-analysis projects, the data preparation step is not only necessary but also vital to find and handle features that could cause some problems while making the quantitative analysis, or that could lead to low efficient coding. According to Alivia Smith[1], this step usually takes up to 80% of the entire time of a data analysis project. Therefore, missing, invalid, and inconsistent values have been addressed. Finally, this step presents a code for changing the format of column names.
# 3.  Exploratory Data Analysis (EDA) and Visualization. Quantitative and qualitative analysis (Asking and Answering Questions).
Although in many cases, the exploratory data analysis and the quantitative and qualitative analysis are separated steps, in this specific project, they have been joined. This step, previous to asking questions that could lead to reaching the project's aim, presents global-useful information about the different columns of the dataset. Some initial examinations were performed as a way of beginning finding patterns, creating hypotheses, and corroborating early assumptions. Later, deeper investigations were depicted as part of reaching the project's goal.

# Quantitative and qualitative analysis: Asking and Answering Questions.
The hypotheses and questions generated to develop this projects are:
1. Which are the strongest Types of Pokemon by Type_1, Type_2.
2. Is there are types that are disproportionality stronger than others.
3. Finding out top 10 winning pokemon combination type.
4. Pokemon with highest winning possibilities
5. which are the strongest Pokemon in the game concerning their Total_score.
6. Which are the strongest and weakest Pokemon?
7. Which is the strongest and weakest generation of Pokemon.
8. Number of Pokemon in each generation
9. what are the factors impacting the Total_points
10. Number of Pokemon are there in each category
11. Number of pokemon in each type in each generation
12. what are diffrent types of species present
13. How many pokemons are of mythical type
14. How many mega type of pokemon are present in the dataset
15. Find out maximum and minimum of each feature
16. Finding mean of each status type of pokemon of each numerical features
17. Catch rate for diffrent status of pokemons
18. What is the growth rate accorting to the type of pokemons
19. Relationship between total points and other features
20. Height of pokemons according to types
21. Types of pokemons with egg cycles

# 4. Inferences and Conclusions.
Although all conclusions and answers are exposed in the previous section accordingly to each question, this section also presents, in a concise manner, the most significant insights.





