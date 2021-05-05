
## The Affect of Demographic Factors on Motor Vehicle Fatalaties Across The United States

### Motivation

Over the past 50 years, the number of motor vehicles in the United States has risen over 150 million. While this has resulted in a more efficient means of mobility for many, it has also resulted in a large number of motor vehicle related deaths. 

The goal of this study is to reveal any underlying relationship between demographic charactersics like gender, age and race and motor vehicle fatality patterns.  The data I use is from the [Fatal Analysis Reporting System (FARS)](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars) 2018, which is a record of fatal car accidents recorded by the National Highway Traffic Safety Administration (NTHSA) in 2018. This dataset includes both demographic data, specifically, gender, age and race in one table and accident related data such as manner of collision, time of collision and many more descriptors. Furthermore, FARS contains data of motor vehicle fatalities across the entire United States with more than 35,000 different observations. 

I hypothesize that there will be some corellation between demographic descriptors and car accident data. This is justified only heuristically by intuition. For example, intuitively, higher age might be corellated with accidents happening later in the night since the visibility is lower and eyesight degrades for a human being as one gets older.  

### Questions
These are the questions I will be looking at: 
#### 1. Do gender, age, race affect where a fatal accident occured as demarated by State, by whether the road is rural or urban, or by the type of road at which the accident occured (interstate, US highway, state highway, county road, or local street)?  
According to the [National Highway Traffic Safety Administration (NTHSA)](https://www.nhtsa.gov/sites/nhtsa.gov/files/811093.pdf) older adult drivers are less likely to have a car accident when on interstate but are more likely to have accidents on county roads with speed limits of 35mph or less. Contrastingly, the opposite is true for young drivers. This is a somewhat shocking fact and I wish to reveal this pattern in the FARS dataset as well. 

I also wish to expand the discrimating demographic feature to gender and race as well, as they might reveal new patterns as it relates to where fatal accidents take place. 
#### 2. Do gender, age, or race affect the severity of injury from an accident? 
According to the [Insurance Institute for Highway Safety (IIHS)](https://www.iihs.org/news/detail/vehicle-choice-crash-differences-help-explain-greater-injury-risks-for-women), women are more at risk at getting injured in a car accident than man, not only because of their physiological differences but also because of the cars each gender tends to drive more. It was found that because women  tend to drive smaller cars, they are more vulnerable to injury in the case of an accident. 
I wish to verify this relationship as well as explore a similar relationship with age or race as the discriminating feature. 

#### 3. Do gender, age, or race affect the manner of Collision (front-to-rear, sideswipe, etc.)? What about the object collided with (Motor vehicle, Collision with Fixed Object, Collission with moving object, etc.)? 

This question is motivated by a number of factors and is indirectly more of a biological question. Are there certain objects people of a certain age, race or gender are not as sensitive too? For example, are the aged more likely to hit a fixed object than those who are younger? 

#### 4. Does age affect time of day an accident occurs? 

According to [Nature](https://www.nature.com/articles/srep00278) Presbyopia is the condition that causes eyesight to worsen as one ages. It is well known that it is harder to see in the dark when driving than in the daylight. This motivates this research question, as to whether age and implicitly eyesight is a determinant factor to the time of day accidents occur. I hypothesize that more aged people will have accidents during the night because of this very reason. 

### Ethical Concerns

* It is always a concern when studies show correlations between demographic data and something happening. This is because to the public and stakeholders involved, a causaility relationship may sometimes be unwillingly implied. This can lead to discrimination against implicated social groups.
*  Stakeholders of this study include but are not limited to drivers, those who live or work in an area with roads, policy makers, hospital workers who care for the injured, those who construct roads and many more secondary stakeholders. 
* The results of such a study may result in conflict in agenda between some of the  stakeholders. For example, policy makers may make policies in aim of reducing accidents but that result in limited mobility of certain drivers from a social group. 
