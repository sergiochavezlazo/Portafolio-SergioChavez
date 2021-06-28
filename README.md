# <h1><center><font color='black'>Pokemon's Stats Analysis</font> </center></h1>

*Sergio Chavez Lazo*

*24 of June 2021*

![image info](data:image/png;base64,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)
    
**This is my first project on my path to become a data analyst** and I cannot imagine a better way to start it than using a dataset that reminds me one of my favorite series of all time: Pokemon. 

I will answer 9questions that I have always have about pokemons by using my basic coding skills. The questions are:

1. Which is the generation with more legendaries?
2. Which is the generation with more megas?
3. If we choose the best pokemon for each feature (Attack, Defense, etc,) how would the team look like?
3. If we choose the best legendary pokemon for each feature (Attack, Defense, etc,) how would the team look like?
4. What could be a good way to categorize non-legendary nor megas pokemons based on their Total Stats? 
4. If we choose the best pokemon for each feature in every type of pokemon, how would the team look like for each type? Which team would be the more balanced?
5. Is there any significative difference on Total's among all the types? (ANOVA)
6. Is there any correlation between features? Is this correlation more or less strong among each generation?
7. Is there any asociation between been legendary and first type of pokemon? (Chi square)
8. Can we predict if one pokemon is legendary or not based on his total? (Logistic Regression)

I will use the dataset provided by Keith Galli in one of the most [helpful tutorial](https://www.youtube.com/watch?v=vmEHCJofslg&t=1226s) I have ever seen to use Pandas



## Getting and cleaning the data

###  A. Getting the data from github

To get the data and start cleaning it, we need our first library [pandas](https://pandas.pydata.org/). We notice that the dataset is in a csv file, so we import it with the function read_csv. Since now, the df object would be the original dataset


```python
import pandas as pd

url='https://raw.githubusercontent.com/sergiochavezlazo/pandas/master/pokemon_data.csv'
df=pd.read_csv(url)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Bulbasaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>45</td>
      <td>49</td>
      <td>49</td>
      <td>65</td>
      <td>65</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Ivysaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>60</td>
      <td>62</td>
      <td>63</td>
      <td>80</td>
      <td>80</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>80</td>
      <td>82</td>
      <td>83</td>
      <td>100</td>
      <td>100</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>VenusaurMega Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>80</td>
      <td>100</td>
      <td>123</td>
      <td>122</td>
      <td>120</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Charmander</td>
      <td>Fire</td>
      <td>NaN</td>
      <td>39</td>
      <td>52</td>
      <td>43</td>
      <td>60</td>
      <td>50</td>
      <td>65</td>
      <td>1</td>
      <td>False</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>795</th>
      <td>719</td>
      <td>Diancie</td>
      <td>Rock</td>
      <td>Fairy</td>
      <td>50</td>
      <td>100</td>
      <td>150</td>
      <td>100</td>
      <td>150</td>
      <td>50</td>
      <td>6</td>
      <td>True</td>
    </tr>
    <tr>
      <th>796</th>
      <td>719</td>
      <td>DiancieMega Diancie</td>
      <td>Rock</td>
      <td>Fairy</td>
      <td>50</td>
      <td>160</td>
      <td>110</td>
      <td>160</td>
      <td>110</td>
      <td>110</td>
      <td>6</td>
      <td>True</td>
    </tr>
    <tr>
      <th>797</th>
      <td>720</td>
      <td>HoopaHoopa Confined</td>
      <td>Psychic</td>
      <td>Ghost</td>
      <td>80</td>
      <td>110</td>
      <td>60</td>
      <td>150</td>
      <td>130</td>
      <td>70</td>
      <td>6</td>
      <td>True</td>
    </tr>
    <tr>
      <th>798</th>
      <td>720</td>
      <td>HoopaHoopa Unbound</td>
      <td>Psychic</td>
      <td>Dark</td>
      <td>80</td>
      <td>160</td>
      <td>60</td>
      <td>170</td>
      <td>130</td>
      <td>80</td>
      <td>6</td>
      <td>True</td>
    </tr>
    <tr>
      <th>799</th>
      <td>721</td>
      <td>Volcanion</td>
      <td>Fire</td>
      <td>Water</td>
      <td>80</td>
      <td>110</td>
      <td>120</td>
      <td>130</td>
      <td>90</td>
      <td>70</td>
      <td>6</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
<p>800 rows × 12 columns</p>
</div>



### B. First changes

By checking the dataset, there are four major changes we want to apply before we start the analysis. 

- Replace the NaN values in the column "Type 2"
- Calculate a new column "Total Stats" that sum all the feature of every pokemon
- Give a name to each generation 
- Create a new column that woul help us to know the numer of pokemons.

**Replace the NaN values in the column "Type 2"**


```python
df.fillna(0, inplace=True)
```

**Calculate a new column "Total Stats" that sum all the feature of every pokemon**


```python
df["Total"]=df.iloc[:,4:10].sum(axis=1)
```

**Give a name to each generation** *(Be aware that = mean assing, and == means equal)*


```python
generation=["Kanto","Jhoto","Hoenn","Sinnoh","Teselia","Kalos"]
df["Labeled generation"]=1

for i in range (6):
    df.loc[df["Generation"]==i+1, "Labeled generation"]=generation[0+i]
    i=+1
```

**Create a new column that would help us to know the number of pokemons.**


```python
df["N° of pokemon"]=1
```

**Check if some values are correct. For instance, check if Mew is labeled as legendary**


```python
#Check which is the state of Mew

df.loc[df["Name"]=="Mew"]
    
#We know have the index value of Mew in the ROWS (165)

df.columns.get_loc("Legendary")

#We now also know the index of the COLUMN (11)

df.iloc[165,11]=True

#Then, we just have to check it

df.loc[df["Name"]=="Mew"]

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
      <th>Total</th>
      <th>Labeled generation</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>165</th>
      <td>151</td>
      <td>Mew</td>
      <td>Psychic</td>
      <td>0</td>
      <td>100</td>
      <td>100</td>
      <td>100</td>
      <td>100</td>
      <td>100</td>
      <td>100</td>
      <td>1</td>
      <td>True</td>
      <td>600</td>
      <td>Kanto</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



**Now lets just take note of some basic coding for exploration**


```python
#Search the columns of your dataset
df.columns
#Find the possible values in one column (for this command, the () makes the difference)
df["Type 1"].unique()
#Check the datatypes in the dataset
df.dtypes
```




    #                      int64
    Name                  object
    Type 1                object
    Type 2                object
    HP                     int64
    Attack                 int64
    Defense                int64
    Sp. Atk                int64
    Sp. Def                int64
    Speed                  int64
    Generation             int64
    Legendary               bool
    Total                  int64
    Labeled generation    object
    N° of pokemon          int64
    dtype: object



### C. Creating subsets

Now, we want to create 4 subsets, one that excludes legendaries, and one that excludes legendaries and megas, one that just contains legendaries and one that just contains megas


```python
#Dataset without legendaries

df_nl=df.loc[df["Legendary"]==False]
```


```python
#Dataset without legendaries and megas

df_nop=df.loc[(~df["Name"].str.contains("Mega"))&(df["Legendary"]==False)]
```


```python
#Dataset of just legendaries (no mega legendaries)

df_leg=df.loc[df["Legendary"]==True]

df_leg=df_leg.loc[~df_leg["Name"].str.contains("Mega")]

```




    (60, 15)




```python
#Dataset with just Megas
df_megas=df.loc[df["Name"].str.contains("Mega")]
```

## Question 1. Which is the generation with more legendaries?

To answer this question we will have to apply the function groupby and agg (this command is very helpful, flexible and precise)


```python
df_leg.groupby(["Labeled generation","Generation"]).agg({"N° of pokemon":"count"}).sort_values("Generation",ascending=True)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>N° of pokemon</th>
    </tr>
    <tr>
      <th>Labeled generation</th>
      <th>Generation</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Kanto</th>
      <th>1</th>
      <td>7</td>
    </tr>
    <tr>
      <th>Jhoto</th>
      <th>2</th>
      <td>5</td>
    </tr>
    <tr>
      <th>Hoenn</th>
      <th>3</th>
      <td>18</td>
    </tr>
    <tr>
      <th>Sinnoh</th>
      <th>4</th>
      <td>13</td>
    </tr>
    <tr>
      <th>Teselia</th>
      <th>5</th>
      <td>15</td>
    </tr>
    <tr>
      <th>Kalos</th>
      <th>6</th>
      <td>8</td>
    </tr>
  </tbody>
</table>
</div>



Now lets plot the results. To do this, we will need new libraries: matplotlib and seaborn


```python
import matplotlib as plt
import seaborn as sns
import matplotlib.pyplot as plt
```


```python
plot1=df_leg.groupby(["Labeled generation","Generation"]).agg({"N° of pokemon":"count"}).sort_values("Generation",ascending=True)

plot1=pd.DataFrame(plot1)

plot1.reset_index(inplace=True)

plot1.columns
```




    Index(['Labeled generation', 'Generation', 'N° of pokemon'], dtype='object')




```python
ax1=sns.barplot(data=plot1, x="Labeled generation", y="N° of pokemon")

ax1.set(title="Figure 1: Legendaries per generation",ylabel="N° of legendaries",xlabel="Generation",ylim=(0, 20))
plt.show()
```


    
![png](output_27_0.png)
    


## Question 2. Which is the generation with more megas?

To answe this question we will have to use the groupby command and agg. 


```python
plot2 = df_megas.groupby(["Labeled generation","Generation"]).agg({"N° of pokemon":"count"}).sort_values("Generation",ascending=True)

plot2=pd.DataFrame(plot2)

plot2.reset_index(inplace=True)

plot2
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Labeled generation</th>
      <th>Generation</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Kanto</td>
      <td>1</td>
      <td>15</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Jhoto</td>
      <td>2</td>
      <td>7</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Hoenn</td>
      <td>3</td>
      <td>20</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Sinnoh</td>
      <td>4</td>
      <td>5</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Teselia</td>
      <td>5</td>
      <td>1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Kalos</td>
      <td>6</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



Now lets plot the results


```python
ax2=sns.barplot(data=plot2, x="Labeled generation",y="N° of pokemon")

ax2.set(title="Figure 2: Number of megas in each generation",ylabel="N° of Megas", xlabel="Generation")
plt.show()
```


    
![png](output_31_0.png)
    


**Interpretation of Q1 and Q2**: *The results of question 1 and 2 show that Hoenn is the generation with more legendaries and more Megas until this moment. This could be the reason why this region is considered the best generation among the pokemon fans community.*

## QUESTION 3. If we choose the best pokemon for each feature (Attack, Defense, etc,) how would the team look like?


```python
df_b1=df_nop.sort_values("Speed",ascending=False).head(1)
df_b1

best_pokemons=[]
```


```python
for e in range(6):
        a="df_n"
        b=str(features[e])
        globals()[a+b]=df_nop.sort_values(features[e],ascending=False).head(1)
        best_pokemons.append(globals()[a+b])
        e=+1
    
#Be careful of not running this cell more than one time because you will still appending more objects to the list best_pokemons
```


```python
#Now we give the dataframe the format of pandas

import numpy as np

best_pokemons=pd.DataFrame(np.row_stack(best_pokemons))

namescolumns=df.columns

best_pokemons.columns=namescolumns

best_pokemons
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
      <th>Total</th>
      <th>Labeled generation</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>242</td>
      <td>Blissey</td>
      <td>Normal</td>
      <td>0</td>
      <td>255</td>
      <td>10</td>
      <td>10</td>
      <td>75</td>
      <td>135</td>
      <td>55</td>
      <td>2</td>
      <td>False</td>
      <td>540</td>
      <td>Jhoto</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>409</td>
      <td>Rampardos</td>
      <td>Rock</td>
      <td>0</td>
      <td>97</td>
      <td>165</td>
      <td>60</td>
      <td>65</td>
      <td>50</td>
      <td>58</td>
      <td>4</td>
      <td>False</td>
      <td>495</td>
      <td>Sinnoh</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>213</td>
      <td>Shuckle</td>
      <td>Bug</td>
      <td>Rock</td>
      <td>20</td>
      <td>10</td>
      <td>230</td>
      <td>10</td>
      <td>230</td>
      <td>5</td>
      <td>2</td>
      <td>False</td>
      <td>505</td>
      <td>Jhoto</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>681</td>
      <td>AegislashBlade Forme</td>
      <td>Steel</td>
      <td>Ghost</td>
      <td>60</td>
      <td>150</td>
      <td>50</td>
      <td>150</td>
      <td>50</td>
      <td>60</td>
      <td>6</td>
      <td>False</td>
      <td>520</td>
      <td>Kalos</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>213</td>
      <td>Shuckle</td>
      <td>Bug</td>
      <td>Rock</td>
      <td>20</td>
      <td>10</td>
      <td>230</td>
      <td>10</td>
      <td>230</td>
      <td>5</td>
      <td>2</td>
      <td>False</td>
      <td>505</td>
      <td>Jhoto</td>
      <td>1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>291</td>
      <td>Ninjask</td>
      <td>Bug</td>
      <td>Flying</td>
      <td>61</td>
      <td>90</td>
      <td>45</td>
      <td>50</td>
      <td>50</td>
      <td>160</td>
      <td>3</td>
      <td>False</td>
      <td>456</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>



*If we check the dataframe that we have just created, we will notice that Shucckle is the pokemon with the best defense and Sp. Defense. In order to not repeat the same pokemon twice, we will erase one row and append the next pokemon*

### Droping duplicate values based on one criteria (or column)
Be aware that it would drop the second row, so if you want to eliminate the first row, just change the order of the dataframe


```python
best_pokemons.drop_duplicates(subset="Name",inplace=True)
```


```python
df_florges=df_nop.sort_values("Sp. Def",ascending=False).head(2)

df_florges1=df_florges.iloc[1]

pd.DataFrame(df_florges1)

best_pokemons=best_pokemons.append(df_florges1)

best_pokemons
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
      <th>Total</th>
      <th>Labeled generation</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>242</td>
      <td>Blissey</td>
      <td>Normal</td>
      <td>0</td>
      <td>255</td>
      <td>10</td>
      <td>10</td>
      <td>75</td>
      <td>135</td>
      <td>55</td>
      <td>2</td>
      <td>False</td>
      <td>540</td>
      <td>Jhoto</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>409</td>
      <td>Rampardos</td>
      <td>Rock</td>
      <td>0</td>
      <td>97</td>
      <td>165</td>
      <td>60</td>
      <td>65</td>
      <td>50</td>
      <td>58</td>
      <td>4</td>
      <td>False</td>
      <td>495</td>
      <td>Sinnoh</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>213</td>
      <td>Shuckle</td>
      <td>Bug</td>
      <td>Rock</td>
      <td>20</td>
      <td>10</td>
      <td>230</td>
      <td>10</td>
      <td>230</td>
      <td>5</td>
      <td>2</td>
      <td>False</td>
      <td>505</td>
      <td>Jhoto</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>681</td>
      <td>AegislashBlade Forme</td>
      <td>Steel</td>
      <td>Ghost</td>
      <td>60</td>
      <td>150</td>
      <td>50</td>
      <td>150</td>
      <td>50</td>
      <td>60</td>
      <td>6</td>
      <td>False</td>
      <td>520</td>
      <td>Kalos</td>
      <td>1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>291</td>
      <td>Ninjask</td>
      <td>Bug</td>
      <td>Flying</td>
      <td>61</td>
      <td>90</td>
      <td>45</td>
      <td>50</td>
      <td>50</td>
      <td>160</td>
      <td>3</td>
      <td>False</td>
      <td>456</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
    <tr>
      <th>739</th>
      <td>671</td>
      <td>Florges</td>
      <td>Fairy</td>
      <td>0</td>
      <td>78</td>
      <td>65</td>
      <td>68</td>
      <td>112</td>
      <td>154</td>
      <td>75</td>
      <td>6</td>
      <td>False</td>
      <td>552</td>
      <td>Kalos</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>




```python
feature=["HP", "Attack","Defense","Sp. Atk","Speed","Sp. Defense"]

for e in range(6):
    print("Based on", feature[e],"the best non legendary pokemon is:", best_pokemons.iloc[e,1])
```

    Based on HP the best non legendary pokemon is: Blissey
    Based on Attack the best non legendary pokemon is: Rampardos
    Based on Defense the best non legendary pokemon is: Shuckle
    Based on Sp. Atk the best non legendary pokemon is: AegislashBlade Forme
    Based on Speed the best non legendary pokemon is: Ninjask
    Based on Sp. Defense the best non legendary pokemon is: Florges
    


HP | Attack| Defense| Sp.Attack| Speed| Sp. Defense
- | - | -| -| -| -
<img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/242.png" alt="Drawing" style="width: 500px;"/> | <img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/409.png" alt="Drawing" style="width: 500px;"/> |<img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/213.png" alt="Drawing" style="width: 500px;"/>|<img src="https://gamepress.gg/pokemonmasters/sites/pokemonmasters/files/styles/300h/public/2019-08/pm0746_12_sword3_256.ktx.png?itok=QaQSMD01" alt="Drawing" style="width: 500px;"/>|<img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/291.png" alt="Drawing" style="width: 500px;"/>|<img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/671.png" alt="Drawing" style="width: 500px;"/>

## QUESTION 4. If we choose the best legendary pokemon for each feature (Attack, Defense, etc,) how would the team look like?

This is the same question but applied for the dataset that only contains legendaries


```python
speciality=["HP","Attack","Defense","Sp. Atk", "Sp. Def","Speed"]
best_legendary=[]

for i in range(6):
    ji=df_leg.sort_values(speciality[i],ascending=False).head(1)
    best_legendary.append(ji)
```


```python
legendaries=pd.DataFrame(np.row_stack(best_legendary))

columns=df_leg.columns             
    
legendaries.columns=columns
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
      <th>Total</th>
      <th>Labeled generation</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>487</td>
      <td>GiratinaAltered Forme</td>
      <td>Ghost</td>
      <td>Dragon</td>
      <td>150</td>
      <td>100</td>
      <td>120</td>
      <td>100</td>
      <td>120</td>
      <td>90</td>
      <td>4</td>
      <td>True</td>
      <td>680</td>
      <td>Sinnoh</td>
      <td>1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>386</td>
      <td>DeoxysAttack Forme</td>
      <td>Psychic</td>
      <td>0</td>
      <td>50</td>
      <td>180</td>
      <td>20</td>
      <td>180</td>
      <td>20</td>
      <td>150</td>
      <td>3</td>
      <td>True</td>
      <td>600</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>377</td>
      <td>Regirock</td>
      <td>Rock</td>
      <td>0</td>
      <td>80</td>
      <td>100</td>
      <td>200</td>
      <td>50</td>
      <td>100</td>
      <td>50</td>
      <td>3</td>
      <td>True</td>
      <td>580</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>382</td>
      <td>KyogrePrimal Kyogre</td>
      <td>Water</td>
      <td>0</td>
      <td>100</td>
      <td>150</td>
      <td>90</td>
      <td>180</td>
      <td>160</td>
      <td>90</td>
      <td>3</td>
      <td>True</td>
      <td>770</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>378</td>
      <td>Regice</td>
      <td>Ice</td>
      <td>0</td>
      <td>80</td>
      <td>50</td>
      <td>100</td>
      <td>100</td>
      <td>200</td>
      <td>50</td>
      <td>3</td>
      <td>True</td>
      <td>580</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>386</td>
      <td>DeoxysSpeed Forme</td>
      <td>Psychic</td>
      <td>0</td>
      <td>50</td>
      <td>95</td>
      <td>90</td>
      <td>95</td>
      <td>90</td>
      <td>180</td>
      <td>3</td>
      <td>True</td>
      <td>600</td>
      <td>Hoenn</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
</div>




```python
for i in range(6):
    print("Based on",feature[i],"the best legendary is:",legendaries.iloc[i,1])
```

    Based on HP the best legendary is: GiratinaAltered Forme
    Based on Attack the best legendary is: DeoxysAttack Forme
    Based on Defense the best legendary is: Regirock
    Based on Sp. Atk the best legendary is: KyogrePrimal Kyogre
    Based on Speed the best legendary is: Regice
    Based on Sp. Defense the best legendary is: DeoxysSpeed Forme
    

HP|Attack|Defense|Sp. Attack|Sp. Defense|Speed
-|-|-|-|-|-
<img src="https://www.imore.com/sites/imore.com/files/styles/large/public/field/image/2019/12/pokemon-487-giratina-origin.png" alt="Drawing" style="width: 500px;"/> |<img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/386_f2.png" alt="Drawing" style="width: 500px;"/>|<img src="https://pokemon-project.com/espadaescudo/img/pokemon/377.png" alt="Drawing" style="width: 500px;"/>|<img src="https://2.bp.blogspot.com/-tZ5o7bFUOt0/WzAQQLv0KiI/AAAAAAAABsI/LD1LI610gq4tzzeAfj9hBNgrmv1XxU51ACLcBGAs/s320/Kyogre%2BPrimigenio.png" alt="Drawing" style="width: 500px;"/>|<img src="http://vignette1.wikia.nocookie.net/pokemon/images/b/b2/378Regice_AG_anime.png/revision/latest?cb=20140311090228" alt="Drawing" style="width: 500px;"/>|<img src="https://images.gameinfo.io/pokemon/256/386-14.png" alt="Drawing" style="width: 500px;"/>

## QUESTION 5: What could be a good way to categorize non-legendary nor megas pokemons based on their Total Stats? 

First we need to explore the Totals of all pokemon to figure out which could be the best way to categorize them


```python
ax3=sns.histplot(data=df_nop,x="Total")
ax3.set(title="Distribution of pokemon based on their total",ylabel="N° of pokemons")
plt.show()
```


    
![png](output_50_0.png)
    



```python
ax4=sns.boxplot(data=df_nop,x="Total")
ax4.set(title="Distribution of pokemon")
plt.show()
```


    
![png](output_51_0.png)
    



```python
df_nop.agg({"Total":["mean","min","max","median"]})
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>mean</th>
      <td>405.680174</td>
    </tr>
    <tr>
      <th>min</th>
      <td>180.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>670.000000</td>
    </tr>
    <tr>
      <th>median</th>
      <td>411.000000</td>
    </tr>
  </tbody>
</table>
</div>



The histogram and the boxplot as well as the statistics give us an idea of how the pokemon are distributed based on their total. For instance, we can observe that the first quartile goest up to 320, the second quartile goes up to 410, the third quartile goes up to 500 and the last quartile goes up to 670. 

Based on this data we proposse to categorize pokemons in 4 groups:

- **Very weaks = 180 to 320**
- **Weaks = 321 to 410**
- **Strongs = 411 to 500**
- **Elites = 501 to 670**


```python
df_nop["Level"]="Hola"

for i in range(691):
    if df_nop.iloc[i,12]<321:
        df_nop.iloc[i,15]="Very weak"
    elif df_nop.iloc[i,12]<411:
        df_nop.iloc[i,15]="Weak"
    elif df_nop.iloc[i,12]<501:
        df_nop.iloc[i,15]="Strong"
    elif df_nop.iloc[i,12]<671:
        df_nop.iloc[i,15]="Elite"
```

    <ipython-input-448-36206cb5a13c>:1: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      df_nop["Level"]="Hola"
    C:\Users\User\anaconda3\lib\site-packages\pandas\core\indexing.py:1765: SettingWithCopyWarning: 
    A value is trying to be set on a copy of a slice from a DataFrame.
    Try using .loc[row_indexer,col_indexer] = value instead
    
    See the caveats in the documentation: https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
      isetter(loc, value)
    


```python
df_nop
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>#</th>
      <th>Name</th>
      <th>Type 1</th>
      <th>Type 2</th>
      <th>HP</th>
      <th>Attack</th>
      <th>Defense</th>
      <th>Sp. Atk</th>
      <th>Sp. Def</th>
      <th>Speed</th>
      <th>Generation</th>
      <th>Legendary</th>
      <th>Total</th>
      <th>Labeled generation</th>
      <th>N° of pokemon</th>
      <th>Level</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>Bulbasaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>45</td>
      <td>49</td>
      <td>49</td>
      <td>65</td>
      <td>65</td>
      <td>45</td>
      <td>1</td>
      <td>False</td>
      <td>318</td>
      <td>Kanto</td>
      <td>1</td>
      <td>Very weak</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>Ivysaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>60</td>
      <td>62</td>
      <td>63</td>
      <td>80</td>
      <td>80</td>
      <td>60</td>
      <td>1</td>
      <td>False</td>
      <td>405</td>
      <td>Kanto</td>
      <td>1</td>
      <td>Weak</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>Venusaur</td>
      <td>Grass</td>
      <td>Poison</td>
      <td>80</td>
      <td>82</td>
      <td>83</td>
      <td>100</td>
      <td>100</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
      <td>525</td>
      <td>Kanto</td>
      <td>1</td>
      <td>Elite</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Charmander</td>
      <td>Fire</td>
      <td>0</td>
      <td>39</td>
      <td>52</td>
      <td>43</td>
      <td>60</td>
      <td>50</td>
      <td>65</td>
      <td>1</td>
      <td>False</td>
      <td>309</td>
      <td>Kanto</td>
      <td>1</td>
      <td>Very weak</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5</td>
      <td>Charmeleon</td>
      <td>Fire</td>
      <td>0</td>
      <td>58</td>
      <td>64</td>
      <td>58</td>
      <td>80</td>
      <td>65</td>
      <td>80</td>
      <td>1</td>
      <td>False</td>
      <td>405</td>
      <td>Kanto</td>
      <td>1</td>
      <td>Weak</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>787</th>
      <td>711</td>
      <td>GourgeistSuper Size</td>
      <td>Ghost</td>
      <td>Grass</td>
      <td>85</td>
      <td>100</td>
      <td>122</td>
      <td>58</td>
      <td>75</td>
      <td>54</td>
      <td>6</td>
      <td>False</td>
      <td>494</td>
      <td>Kalos</td>
      <td>1</td>
      <td>Strong</td>
    </tr>
    <tr>
      <th>788</th>
      <td>712</td>
      <td>Bergmite</td>
      <td>Ice</td>
      <td>0</td>
      <td>55</td>
      <td>69</td>
      <td>85</td>
      <td>32</td>
      <td>35</td>
      <td>28</td>
      <td>6</td>
      <td>False</td>
      <td>304</td>
      <td>Kalos</td>
      <td>1</td>
      <td>Very weak</td>
    </tr>
    <tr>
      <th>789</th>
      <td>713</td>
      <td>Avalugg</td>
      <td>Ice</td>
      <td>0</td>
      <td>95</td>
      <td>117</td>
      <td>184</td>
      <td>44</td>
      <td>46</td>
      <td>28</td>
      <td>6</td>
      <td>False</td>
      <td>514</td>
      <td>Kalos</td>
      <td>1</td>
      <td>Elite</td>
    </tr>
    <tr>
      <th>790</th>
      <td>714</td>
      <td>Noibat</td>
      <td>Flying</td>
      <td>Dragon</td>
      <td>40</td>
      <td>30</td>
      <td>35</td>
      <td>45</td>
      <td>40</td>
      <td>55</td>
      <td>6</td>
      <td>False</td>
      <td>245</td>
      <td>Kalos</td>
      <td>1</td>
      <td>Very weak</td>
    </tr>
    <tr>
      <th>791</th>
      <td>715</td>
      <td>Noivern</td>
      <td>Flying</td>
      <td>Dragon</td>
      <td>85</td>
      <td>70</td>
      <td>80</td>
      <td>97</td>
      <td>80</td>
      <td>123</td>
      <td>6</td>
      <td>False</td>
      <td>535</td>
      <td>Kalos</td>
      <td>1</td>
      <td>Elite</td>
    </tr>
  </tbody>
</table>
<p>691 rows × 16 columns</p>
</div>



Now that we have labeled all pokemon based on their total, we will plot the results in a barplot


```python
levelpokemon=df_nop.groupby("Level").agg({"N° of pokemon":"count"})
levelpokemon=levelpokemon.reset_index()
levelpokemon
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Level</th>
      <th>N° of pokemon</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Elite</td>
      <td>118</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Strong</td>
      <td>229</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Very weak</td>
      <td>183</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Weak</td>
      <td>161</td>
    </tr>
  </tbody>
</table>
</div>




```python
ax5=sns.barplot(data=levelpokemon,x="Level",y="N° of pokemon",order=["Very weak","Weak","Strong","Elite"])
ax5.set(title="N° of pokemon in each category based on their total", ylim=(0,250))
plt.show()
```


    
![png](output_58_0.png)
    


To go even further, we can create a barplot that show the difference among generations


```python
levelpokemon3=df_nop.groupby(["Labeled generation","Level"]).agg({"Total":"count"})

levelpokemon3=levelpokemon3.reset_index()

levelpokemon3.sort_values("Level",ascending=True)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Labeled generation</th>
      <th>Level</th>
      <th>Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Hoenn</td>
      <td>Elite</td>
      <td>11</td>
    </tr>
    <tr>
      <th>16</th>
      <td>Sinnoh</td>
      <td>Elite</td>
      <td>33</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Kanto</td>
      <td>Elite</td>
      <td>21</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Jhoto</td>
      <td>Elite</td>
      <td>13</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Kalos</td>
      <td>Elite</td>
      <td>14</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Teselia</td>
      <td>Elite</td>
      <td>26</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Kanto</td>
      <td>Strong</td>
      <td>47</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Sinnoh</td>
      <td>Strong</td>
      <td>28</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Kalos</td>
      <td>Strong</td>
      <td>25</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Jhoto</td>
      <td>Strong</td>
      <td>31</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Teselia</td>
      <td>Strong</td>
      <td>54</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Hoenn</td>
      <td>Strong</td>
      <td>44</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Kalos</td>
      <td>Very weak</td>
      <td>16</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Teselia</td>
      <td>Very weak</td>
      <td>40</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Hoenn</td>
      <td>Very weak</td>
      <td>41</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Kanto</td>
      <td>Very weak</td>
      <td>40</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Jhoto</td>
      <td>Very weak</td>
      <td>26</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Sinnoh</td>
      <td>Very weak</td>
      <td>20</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Sinnoh</td>
      <td>Weak</td>
      <td>22</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Kalos</td>
      <td>Weak</td>
      <td>19</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Jhoto</td>
      <td>Weak</td>
      <td>24</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Hoenn</td>
      <td>Weak</td>
      <td>29</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Kanto</td>
      <td>Weak</td>
      <td>38</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Teselia</td>
      <td>Weak</td>
      <td>29</td>
    </tr>
  </tbody>
</table>
</div>




```python
ax6=sns.barplot(data=levelpokemon3, x="Labeled generation",y="Total",hue="Level",order=['Kanto', 'Jhoto', 'Hoenn', 'Sinnoh', 'Teselia', 'Kalos'],hue_order=['Very weak', 'Weak', 'Strong', 'Elite'])

ax6.set(title="N° of pokemon in each generation based on their total",ylabel="N° of pokemon",xlabel="Generation",ylim=(0,60))
plt.legend(bbox_to_anchor=(1.05, 1), loc=2, borderaxespad=0.)
plt.show()
```


    
![png](output_61_0.png)
    


**Interpretation** Based on the last graphic, we can say that in the fourth generation (Sinnoh) there were introduced more elite pokemon than in any other generation. What is more, in Sinnoh there are more elite pokemon than pokemon of the other three levels we have just created.


```python

```

