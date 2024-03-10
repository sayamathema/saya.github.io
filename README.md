# Posture-Personality

Are you a **hunchbacked hermit** or a **power-posing** peacock? We explore the science behind how you stand and how it reflects who you are (without the awkward staring!). 
Work-related back pain is a prevalent condition that frequently impacts the workforce, leading to disability, increased healthcare needs, and a significant socioeconomic impact. Despite the ongoing mystery surrounding the origin of occupational pain, there is anecdotal evidence suggesting that both personality and posture play roles in the prolonged management of pain, indicating a direct influence of the mind-body axis. This study aims to thoroughly examine the connections between posture and personality.
To understand the correlation and causation of the pain, we took a dataset that studied the relation between a person's level of pain in relation to their posture, personality, height, weight, sex, activity level. [Source: Correlation between Posture & Personality Trait](https://www.kaggle.com/datasets/dhanasekarjaisankar/correlation-between-posture-personality-trait)

The Myers-Briggs Personality Type Indicator is a self-report inventory designed to identify a person's personality type, strengths, and preferences. The questionnaire was developed by Isabel Myers and her mother Katherine Briggs based on their work with Carl Jung's theory of personality types. Today, the MBTI inventory is one of the world's most widely used psychological instruments. [Source: Very Well Mind, How the Myers-Briggs Type Indicator Works](https://www.verywellmind.com/the-myers-briggs-type-indicator-2795583)

There are 16 different MBTI types shown as below.![Screenshot 2024-03-02 153538](https://github.com/sayamathema/posture-personality/assets/110393954/0226b16e-c102-4b01-b4a4-f4ff489bbd3e)
In the dataset, there are 4 types of posture type; Posture A, Posture B, Posture C and Posture D. Posture A being the best posture type while Posture D being the worst posture type. 
## Analysis of Data 
#### Analysis of Posture and Sex
The total population of the dataset was 97. The highest number of posture type was posture B with 36 participants having that posture type (37.11%), Posture A was second on the list with 22 individuals possesing such posture type (22.68%), Psoture D was third with 20 individuals having such posture type(20.62%) and Posture C was the least in the list with 19 individuals having such type of posture (19.59%). 

![image](https://github.com/sayamathema/posture-personality/assets/110393954/0ad0ee02-21f3-4aa9-b76a-fb8b903e55b6)

The data has almost equal composition of male and female. Out of 97, 49 are female and 48 are male. 

![image](https://github.com/sayamathema/posture-personality/assets/110393954/35050c7e-76d7-4cb9-8d28-3c2a10ede0a1)

When comparing the sex and posture type, it was found that male had more composition for Posture A type than their female counterpart, females had more composition for Posture B type, males had more composition in Posture C type and females had more composition in Posture D.
![image](https://github.com/sayamathema/posture-personality/assets/110393954/56c7ae1e-4db7-4ff3-97d1-408748984308)

Expressing the above in numbers, among the total posture A type, male constituted of 59.09%. 55.56% of the total Posture B population constituted of female. 57.89% of the posture C type population were male while 60% of posture D population were female. 
![image](https://github.com/sayamathema/posture-personality/assets/110393954/0ece7a5b-93f6-42aa-8cc0-07fbafdd280b)


#### Analysis of Posture and Personality type
![image](https://github.com/sayamathema/posture-personality/assets/110393954/2408ec51-cb5d-4928-935f-56c0f42e4769)

ESFP  had the highest Count of MBTI and was 1,100.00% higher than INTJ, which had the lowest Count of MBTI at 1.﻿ The ESFP personality type, characterized by Extraversion, Sensing, Feeling, and Perceiving, is a vibrant and outgoing individual who thrives in social interactions. Highly observant and practical, ESFPs focus on the present moment, making decisions based on personal values and fostering harmonious relationships. With a playful and energetic nature, they enjoy spontaneity and adaptability, often embracing new experiences and taking risks. Tactile and hands-on, ESFPs are skilled at dealing with practical, tangible issues and may have a keen aesthetic sense. While they may avoid conflict, their enthusiastic and lively approach to life makes them engaging and often the life of the party. 
The INTJ personality type, according to the Myers-Briggs Type Indicator (MBTI), stands for Introverted, Intuitive, Thinking, and Judging. INTJs are known for their strategic and analytical thinking, often seeking to understand complex systems and solve intricate problems. As introverts, they prefer solitude for deep contemplation, but they can articulate their ideas clearly and persuasively when needed. With a strong focus on the future, INTJs are forward-thinking and visionary, relying on intuition to anticipate possibilities and trends. Their decisions are typically logic-driven, and they value efficiency and competence in both themselves and others. While they may appear reserved, INTJs can be visionary leaders with a goal-oriented and decisive approach to achieving their objectives.
**So if we are to follow the data, most people in our society,are outgoing, playful, energetic and comfortable taking risk.**

Upon trying to analyse the relation between the posture and the individual but contrasting personality type, we found out the following relationship. 

##### Extraversion and Introversion
It is seen that those with Posture A and Posture B had more extraversion traits compared to those having Psture C and Posture D. 
Extraversion (also spelled Extroversion) is a personality trait characterized by an outgoing, social, and energetic nature. Individuals with high extraversion levels tend to enjoy interacting with others, are often talkative, and find energy in social situations. They may also be more assertive and enthusiastic.

In contrast, introversion is a personality trait marked by a preference for solitude, quiet environments, and a lower level of social stimulation. Introverted individuals may need time alone to recharge and may prefer deeper one-on-one interactions rather than large social gatherings. They are often reflective, observant, and thoughtful.

It could be that those with extroverts' tendency to engage more actively in social interactions, where maintaining an upright and confident posture is often emphasized could result to the above outcome. However, it needs to be noted that individual habits, physical health, and self-awareness play significant roles in posture and can vary widely among both extroverts and introverts.

![image](https://github.com/sayamathema/posture-personality/assets/110393954/38838d12-d83d-43cd-820e-509925a18497)

##### Feeling, Thinking and Sensing
Analysing the Feeling, Sensing and Thinking aspect, it shows that those with Sensing traits have the most Posture A. Sensing traits might be more attentive to their immediate surroundings and physical sensations, contributing to awareness of posture.
Individuals with a Feeling preference make decisions based on personal values and the impact on people. They tend to consider the emotional aspects of a situation, prioritize harmony, and value interpersonal relationships. F types often seek consensus and may make decisions with a focus on empathy and compassion.
Thinking individuals make decisions based on logic, analysis, and objective criteria. They prioritize fairness, consistency, and objective facts over personal values. T types may appear more detached or analytical in decision-making, relying on reason rather than emotional considerations.
Sensing individuals prefer to focus on the present and concrete details. They are practical, realistic, and observant of their immediate surroundings. S types often rely on information obtained through their senses and are adept at dealing with tangible, real-world data. They value hands-on experience and tend to be more grounded in the present moment.


![image](https://github.com/sayamathema/posture-personality/assets/110393954/75afefe1-e2b5-4de7-bed1-1516e5d096c7)
##### Judging and Perceiving  
We also found that people with perceiving traits compared with people havingjuding traits to have better posture. Individuals with a Judging preference tend to be organized, structured, and decisive in their approach to life. They like planning, making schedules, and having a clear framework for tasks. J types often prefer closure and enjoy having things settled. They are typically goal-oriented, focused on achieving objectives, and may feel more comfortable when tasks are planned and organized. Perceiving individuals, on the other hand, are more flexible, spontaneous, and adaptable. They prefer to go with the flow, keeping options open rather than settling quickly. P types often enjoy exploration, improvisation, and may postpone decision-making until they gather more information. They are generally more comfortable with uncertainty and enjoy the freedom to adapt to changing circumstances.
﻿ 

  ![image](https://github.com/sayamathema/posture-personality/assets/110393954/5146be51-361d-4929-a403-0852e3e33ae0)
Sum of PAIN 1 and total Sum of PAIN 4 are negatively correlated with each other. C had 33 Sum of PAIN 1, 40 Sum of PAIN 4, and 24 Sum of PAIN 3. ﻿B had 91 Sum of PAIN 1, 98.50 Sum of PAIN 4, and 79 Sum of PAIN 3. A had 42 Sum of PAIN 1, 47 Sum of PAIN 4, and 30 Sum of PAIN 3. D had 41.50 Sum of PAIN 1, 60 Sum of PAIN 4, and 55.50 Sum of PAIN 3. ﻿At 91, B had the highest Sum of PAIN 1 and was 175.76% higher than C, which had the lowest Sum of PAIN 1 at 33.﻿﻿
﻿﻿
﻿﻿Sum of PAIN 1 and total Sum of PAIN 4 are positively correlated with each other.﻿﻿
﻿﻿
﻿﻿B accounted for 43.86% of Sum of PAIN 1.﻿﻿
﻿﻿
﻿﻿Across all 4 POSTURE, Sum of PAIN 1 ranged from 33 to 91, Sum of PAIN 4 ranged from 40 to 98.50, and Sum of PAIN 3 ranged from 24 to 79.﻿﻿.

![image](https://github.com/sayamathema/posture-personality/assets/110393954/d376e3a1-c480-4891-bd7a-9c45b904afb8)
