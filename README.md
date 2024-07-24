# pokemon_analyst

## Project Overview
This project was conducted to analyze the Pokemon dataset to identify trends and insights that can help players make the good team composition.

The dataset used can be seen at the following link:
https://bit.ly/data-pokemon-dsf

## Project Goals
1. Identify and understand the distribution of Pokémon of different generations and types to provide insight into the trends and popularity of each category.
2. Identify Pokémon with the highest and lowest stats to assist players in building more effective and strategic teams.

## Data Overview
This dataset contains information about various types of Pokémon with the following attributes:
- `#`: ID for each Pokémon
- `Name`: Name of each Pokémon
- `Type 1`: Primary type of each Pokémon
- `Type 2`: Secondary type of some Pokémon
- `Total`: Sum of all stats that follow
- `HP`: Hit points, defines how much damage a Pokémon can withstand
- `Attack`: Base modifier for normal attacks
- `Defense`: Base damage resistance against normal attacks
- `SP Atk`: Special attack modifier
- `SP Def`: Special defense modifier
- `Speed`: Determines which Pokémon attacks first each round

## Tools
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Analysis Summary
### Data Cleaning
- There are 386 missing values in the 'Type 2' column. However, I ignored it as it had no effect on the subsequent analysis..
- Removed the unused `#` column.

### Key Insights
- **Generation Distribution**: Generation 1 has the largest distribution of Pokémon.
- **Type Distribution**: 'Water' is the most common primary type, and 'Flying' is the most common secondary type.
- **Statistical Analysis**:
  - **Top Attack**: Mega Mewtwo X (Attack: 190)
  - **Top Defense**: Shuckle, Mega Steelix, Mega Aggron (Defense: 230)
  - **Top HP**: Blissey (HP: 255)
  - **Top Speed**: Deoxys (Speed Forme) (Speed: 180)
  - **Top Special Attack**: Mega Mewtwo Y (SP Atk: 194)
  - **Top Special Defense**: Shuckle (SP Def: 230)
  - **Top Total**: Mega Rayquaza, Mega Mewtwo X/Y (Total: 780)
 
## Recommendations
1. Use Pokémon from 'Cluster 0' for high attack strategies.
2. Utilize Pokémon with the highest stats according to their element.
3. Combine legendary Pokémon with non-legendary ones that have certain advantages for a more effective strategy.

## Conclusion
The analysis reveals significant insights into the distribution and statistical strengths of various Pokémon, which can aid in strategic game planning.

## Contact
- Email: awnana123@gmail.com
- LinkedIn: [/in/nana-caw/](https://www.linkedin.com/in/nana-caw/)
