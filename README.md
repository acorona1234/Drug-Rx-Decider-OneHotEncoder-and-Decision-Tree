## Introduction:
The field of medical research relies heavily on data analysis and modeling to make informed decisions and improve patient care. In this analysis, we have a dataset that represents a study conducted on patients suffering from the same illness. Each patient responded to one of five medications: Drug A, Drug B, Drug C, Drug X, or Drug Y. The objective is to build a model that can predict which drug would be suitable for future patients with the same illness based on their age, sex, blood pressure, and cholesterol levels. This dataset serves as a sample of a multiclass classifier problem, and we will utilize the training data to construct a decision tree model. The decision tree can then be employed to predict the appropriate medication for an unknown patient or to prescribe a drug to a new patient. This analysis holds the potential to enhance treatment outcomes and aid in personalized medicine.

* [Data Preprocessing](#section-one)
* [Decision Tree](#section-two)
    - [Categorical Features](#subsection-one)
    - [Visualizations](#anything-you-like)
* [Conclusion](#section-three)

  <a id="section-one"></a>

## Data Preprocessing

#### This section will go over handling missing values as well as feature transformation

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/706aa0e0-92ac-4481-ba52-d5e167c3176d)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/a8299904-f1da-4052-b213-2f144f5d4ec0)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/aeae42e4-52ba-4fe5-9bf7-d508d0a2d4ed)


<a id="subsection-one"></a>
## One Hot Encoder for categorical features

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/45ace40b-de76-4415-b976-3bfe993f93c4)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/334330c9-e24f-482c-9187-199328e68466)

<a id="section-two"></a>
## Visualizing the Decision Tree
![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/dac9b449-dc84-4d86-8308-ca12da4605f5)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/d948382f-9c17-456d-9588-b107208f4954)

<a id="anything-you-like"></a>
## Visualizations

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/1219476f-ddb7-4af4-9a03-3ffe097357ae)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/9c3783cd-c40e-49a5-bb7a-d6a8f774c644)

![image](https://github.com/acorona1234/Drug-Rx-Decider-OneHotEncoder-and-Decision-Tree/assets/73566258/bb5b6676-4e88-41db-9eb5-8d0040639678)

<a id="section-three"></a>
## Conclusion:
In this analysis, I delved into a dataset encompassing patients who shared the same illness and responded to various medications. By leveraging key features such as age, sex, blood pressure, cholesterol levels, and the Sodium-Potassium ratio (Na_to_K), I constructed a decision tree model to predict the most suitable drug for future patients with similar conditions. My findings shed light on crucial insights that can significantly impact medical decision-making and patient care.

Firstly, I discovered that drug Y emerges as the drug of choice for patients whose Sodium-Potassium levels exceed 14.8. This finding implies that individuals with higher Sodium-Potassium ratios tend to respond favorably to drug Y, making it a preferred medication in such cases. This insight holds immense value in tailoring treatment plans to optimize patient outcomes and improve their overall well-being.

Additionally, I observed that drug X is primarily administered to patients with high blood pressure. This insight highlights the importance of considering specific patient characteristics, such as blood pressure levels, to determine the appropriate medication. By identifying drug X as the recommended choice for individuals with high blood pressure, we can enhance the precision and efficacy of treatment regimens.

By incorporating these findings into medical practice, healthcare professionals can make more informed decisions when prescribing medications to patients with similar illnesses. This personalized approach based on individual patient attributes can potentially lead to improved treatment outcomes, reduced adverse effects, and enhanced patient satisfaction.

Through the application of data analysis and machine learning techniques, this study contributes to the advancement of personalized medicine. By harnessing the power of algorithms and leveraging comprehensive datasets, I can optimize treatment strategies, minimize trial-and-error approaches, and ultimately improve the quality of life for patients. These findings underscore the pivotal role that data-driven approaches play in shaping the future of healthcare and highlight the immense potential for further research and advancements in medical decision-making.





