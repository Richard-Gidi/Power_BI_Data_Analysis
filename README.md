# U.S Police Shootings-Dashboard

## Problem Statement
In light of the recent discussions surrounding police killings in the United States, particularly the issue of racism, this project aims to analyze a dataset that sheds light on this critical topic. By examining the data, we seek to extract insights and analyze the narratives surrounding racism in America.

## Dataset
The dataset used contained 15 columns
- **Victim Information**:
  - Name
  - Age
  - Gender
  - Race
  - id

- **Incident Information**:
  - Date of the event
  - Location of the incident
  - Method of shooting (e.g., firearm, taser)
  - Circumstances of the incident (e.g., did they attack?)
  - Presence of weapons
  - Signs of mental illness
  - Whether the police officer was equipped with a body camera
  - Whether the suspect fled

- **Weapon Category**: A categorical column indicating the type of weapon used by the suspect.


## Data Processing

The dataset contains **15 columns** with no missing values, ensuring a clean dataset for analysis. Below are the key steps taken during the data processing phase:

1. **Age Grouping**: 
Created a new column that groups ages into specific ranges to analyze the age distribution of individuals killed by police. The age ranges include:
- 0-14
- 15-34
- 35-54
- 55-74
- 75 and Above

2. **Gender Encoding**: 
The gender column, originally encoded with "M" and "F", was updated to more descriptive terms: "Male" and "Female".

3. **State Abbreviations**: 
The two data were modeled to facilitate easier analysis and visualization.The states in the dataset were abbreviated (e.g., Ohio as OH). To enhance clarity, a new dataset containing the names of states and their abbreviations was imported into the workspace.


### Overview Dashboard
**Total Shootings by Gender** : A significant majority of victims (95.46%) are male, with females accounting for only 4.54%.

**Total Shootings by Race** : The data shows that White victims (2,476) were the most affected, followed by Black (1,298) and Hispanic (902) individuals.

**Total Shootings by Age Group**: The age group 15-34 has the highest number of police shootings (259), indicating a concerning trend among younger individuals.

**Total Shootings by Month**: March experienced the highest number of shootings (505), while the trend shows a gradual decline towards the end of the year.

### Individual Dashboard
**Manner of Death**: A vast majority of incidents (94.93%) involved victims being shot, with only a small fraction being shot and tasered.

**Total Shootings by Signs of Mental Illness**: A total of 3.8K victims did not exhibit signs of mental illness, while 1.1K did, highlighting a possible area for intervention.

**Total Shootings by Threat Level**: Most shootings were labeled as attacks (3,160), indicating a high level of perceived threat during these incidents.

**Total Shootings by Armed Category**: Guns were the most common weapon used in shootings (274), with other categories like sharp objects and unarmed individuals also represented.

## Recommendations

While the data indicates that a significant number of White individuals were involved in police shootings, it is essential to contextualize these figures within the broader demographic landscape of the United States. Given that White individuals make up a substantial portion of the overall population, the number of shootings involving White victims may not indicate a disproportionate impact compared to other racial groups.

### Considerations

1. **Demographic Proportions**: 
Acknowledge that while the absolute number of White victims is high, this must be interpreted relative to the demographic makeup of the U.S. population. Recent census data shows that White individuals represent approximately 76% of the U.S. population. Thus, the percentage of White individuals involved in police shootings may align more closely with their population share.

2. **Focus on Disparities**: 
Emphasize the need to explore the disparities in police interactions across different racial groups. While the number of White victims is significant, analyzing the rates of police shootings per capita for minority groups may reveal underlying systemic issues that warrant attention.

3. **Policy Implications**: 
Recommend that policymakers and law enforcement agencies focus on comprehensive strategies that address racial disparities in police encounters. This includes enhanced training, community engagement, and policies aimed at reducing the use of force disproportionately affecting minority communities.

4. **Further Research**: 
Encourage ongoing research into the contextual factors contributing to the incidence of police shootings, such as socioeconomic status, mental health considerations, and community relations. Understanding these variables can help formulate more effective interventions.

By taking these considerations into account, we can foster a more nuanced dialogue around police shootings and work towards equitable solutions that address the complexities of race and policing in America.
