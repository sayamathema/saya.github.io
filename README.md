# Decoding the Relation Between Posture, Personality, and Pain 
##### Authors: Saya Mathema and Kalpana Budha 

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
  
## POSTURE TYPE AND PAIN
Embarking on the intriguing exploration of pain and posture analysis, we dissect four distinct types of discomfort – Neck Pain, Thoracic Pain, Lumbar Pain, and Sacral Pain, each tethered to specific regions of the body. With Neck Pain (PAIN 1), Thoracic Pain (PAIN 2), Lumbar Pain (PAIN 3), and Sacral Pain (PAIN 4) as our focal points, this investigation seeks to unravel correlations, disparities, and captivating patterns within the intricate tapestry of physiology. Our journey through the complexities of posture and its impact on pain unveils a compelling narrative, where the physical and perceptual converge.

Our analysis unravels a spectrum of correlations and disparities among the four types of pain, with a particular focus on Neck Pain (PAIN 1) and Sacral Pain (PAIN 4). The negative correlation between the sum of Neck Pain and the total sum of Sacral Pain hints at a nuanced relationship, challenging conventional expectations. A meticulous examination of individual postures – A, B, C, and D – further illuminates the intricacies of this interplay. Notably, Posture B emerges as a significant contributor, commanding 43.86% of the sum of Neck Pain, showcasing a substantial impact on pain perception.

Diving deeper into the nuances, Posture B stands out with the highest Sum of Neck Pain at 91, a staggering 175.76% higher than the lowest, attributed to Posture C at 33. As we traverse the entire spectrum of postures, from the pinnacle of Posture A to the nadir of Posture D, the variations in Neck Pain, Sacral Pain, and Lumbar Pain underscore the intricate dance between body mechanics and discomfort. Thoracic Pain introduces an additional layer of complexity, spanning from 30 to 153 across all postures, contributing to the multifaceted nature of our investigation.

Unveiling a fascinating twist, Posture B, Posture C, and Posture D collectively experience Neck Pain at its highest and Lumbar Pain at its lowest, adding a layer of intrigue to our understanding of the intricate relationship between posture and pain. This reveals a dynamic interaction, challenging preconceived notions and inviting a deeper exploration into the complexities of the mind-body axis.

In the realm where posture and pain intersect, our analysis illuminates a complex tapestry of relationships, challenges, and unexpected patterns. The negative correlation between Neck Pain and total Sacral Pain prompts us to reconsider conventional wisdom, while the dominance of Posture B in influencing pain perception invites further inquiry. As we navigate the landscape of Posture A, Posture B, Posture C, and Posture D, each unveiling its unique imprint on pain experiences, our understanding deepens, leaving us poised on the precipice of further exploration into the intricate dance between the physical and the perceptual. 

![image](https://github.com/sayamathema/posture-personality/assets/110393954/d376e3a1-c480-4891-bd7a-9c45b904afb8)


## Conclusion
In conclusion, the exploration of the correlation between posture and personality traits, as well as their impact on work-related pain, reveals a nuanced and intricate interplay within the mind-body axis. The dataset analysis sheds light on the prevalence of different posture types, with Posture B being the most common, and intriguingly, individuals with extraverted personality traits are more likely to exhibit Posture A and Posture B. The prevalence of ESFP personality types, characterized by extraversion, aligns with a society where people tend to be outgoing, playful, energetic, and comfortable taking risks.

Further dissecting the relationship between posture and pain, the analysis exposes unexpected patterns and challenges conventional expectations. Notably, Posture B emerges as a significant contributor to Neck Pain, challenging preconceived notions about pain distribution across different postures. The negative correlation between Neck Pain and total Sacral Pain prompts a reconsideration of established beliefs, while the dominance of Posture B in influencing pain perception invites deeper inquiry.

The study underscores the dynamic interaction between personality traits, posture, and pain, emphasizing the need for a holistic approach to understanding the mind-body connection. As society grapples with the impact of work-related pain, this exploration offers a compelling narrative that calls for further investigation into the intricate dance between the physical and the perceptual realms. Ultimately, our analysis encourages a reevaluation of traditional assumptions, paving the way for a more comprehensive understanding of how posture and personality intertwine to shape our experiences and well-being.
