# BCG Gamma Challenge: How can one promote sustainable economic development in municipalities of the Legal Amazon?

##  BCG GAMMA Challenge Winner

We're proud to announce that our team secured the **First Prize in the BCG GAMMA Challenge for Data Science and Consulting**. This GitHub repository hosts all the code, models, and analytical techniques we employed during the competition.


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/1d278b29-4feb-4a56-87f9-441507fb5a3c" alt="Description of Image" width="400px"/>
</p>


BCG GAMMA, a specialized unit of the Boston Consulting Group (BCG) focused on **Data Analytics and Artificial Intelligence (AI)**, has unveiled its latest initiative: the BCG GAMMA Challenge. **This annual event is designed to spotlight emerging talents in Data Science and offer them a platform to tackle genuine issues**.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/cc29aacb-5865-4cf6-9c43-3991722d7ff5" alt="Description of Image" width="600px"/>
</p>


## The Challenge

![BCG](https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/141b7f3f-5220-4e4a-aa43-6e088e4b2eb2)


In its fourth edition, **the challenge invites participants to develop analytical solutions that can drive sustainable economic growth in the Amazon Region, in Brazil**. By harnessing publicly available data from local municipalities—ranging from biomes and exports to agricultural production and deforestation—participants are tasked with uncovering vital insights for the area's future.

The challenge centers on promoting sustainable economic development in the municipalities of the Legal Amazon. **Despite the Amazon's vast economic potential, it faces issues such as low social development, underutilized economic opportunities, and increasing deforestation**. Participants are tasked with analyzing data across environmental, social, and economic dimensions using advanced analytics. **The objective is to derive innovative insights and provide actionable recommendations for the Arapyaú Institute, an important local non-profit organization,  or public entities to drive sustainable growth in the region.**

## Our Solution


### Our Solution - *Context: Forest-compatible Products*

**In the Amazon, we​ have a prevalence of monocultures**. Of the entire area planted within its territory in the year 2019:

* 🌱 **55% soybeans**
* 🌽 **27% corn**

These monocultures result in soil exhaustion, leading to the nutritional degradation of the land. On the other hand, only a small percentage of cities (about 3% in the region) utilize *forest-compatible products*:

*  **Pineapple**
*  **Açaí**
*  **Cocoa**
*  **Robusta Coffee (in bean form)**
*  **Cashew Nut**
*  **Papaya**
*  **Cassava**
*  **Passionfruit**
*  **Watermelon**
*  **Other fruits and vegetables**



By not using forest-compatible products, **these cities are missing out on the global economic potential of these products**:

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/ac52a342-8b6a-4a0c-b8cb-cf9bb0640bf2" alt="Amazon's Participation" width="600px"/>
</p>

---

### Our Solution - *Context: Social Programs in the Amazon Rainforest*

There are a series of **Brazilian​ Government Social Programs** encouraging production in the Legal Amazon, like:​

* **"Auxílio Inclusão Produtiva Rural"**: It is the granting of a monthly financial aid so that the citizen can start investing in their own rural production. Through this benefit, they will receive training from an agricultural technician on managing small-scale farming.
* **"Fomento Rural"**: The Rural Development Program combines social and productive monitoring with direct financial support for poor rural families to invest in productive projects. The goal is to enhance their food production, income generation, and overall well-being, contributing to improved food security and poverty reduction.
* **"Alimenta Brasil"**: is a food acquisition program that supports access to food and encourages production among various traditional groups. Through streamlined procurement, the government buys food from these groups and distributes it to those in need, including families, schools, health facilities, and correctional institutions.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/b5afae52-9b27-4c64-99a6-44bdf47bc23d" alt="Social Programs" width="400px"/>
</p>

While these programs cover **62%** of the families receiving assistance in the region, **they do not mention products suitable for the Amazon rainforest**. This means that there is encouragement for **agriculture without taking into account the local biome and ecological diversity**.

---

### Our Solution - *Proposal*:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/4f7b4a46-5d4d-45ab-b996-25e7a0631e38" alt="Proposal" width="500px"/>
</p>

The primary goal is to provide additional incentives to local families to cultivate products that are compatible with the Amazon rainforest biome. Concurrently, the Brazilian federal government should purchase these products from the families and utilize them for the food supply in its facilities, including hospitals, schools, prisons, and the like.

---

### Our Solution -  *How to select diverse forest-compatible products that are suitable for the biome and climate of each municipality?*

We selected eleven products with the highest production history and analyzed the last ten years to extract the return and risk per municipality.

**The best strategy for selecting the products will be one that focuses on diversity, promoting biodiversity, meeting diverse nutritional and economic needs of local communities, and helping to reduce the risk associated with each product's harvest.**

The choice should take these factors into consideration, **maximizing the income generated (return) from the investment of the Brazilian Government**:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/3c1f057d-df24-42e0-b3a6-e8a01fb5f064" alt="ReturnRisk" width="800px"/>
</p>

---

### Our Solution -  *How to select diverse forest-compatible products that are suitable for the biome and climate of each municipality?*

To choose the distribution of products in each city, we propose a solution (pipeline) that combines two techniques:

* **Machine Learning**: Using soil data for each city (pH, salinity, carbon, and saturation) as well as climate data for each city (temperature, rainfall, wind speed), we can generalize a model that can predict the productivity of each of the forest-compatible products for each city.
* **Metaheuristic Optimization**: Using metaoptimization through a genetic algorithm, given the productivity of each city, we can find the best configuration of products suitable for the biome and climate of each municipality, maximizing the return-profit ratio for the Brazilian government.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/7d21b992-85ff-4638-96c3-5b27d38e0318" alt="ReturnRisk" width="800px"/>
</p>

---

### Our Solution -  *Data*

The training data for the machine learning model consisted of:

1. **Soil data for each city**:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/236eacaf-2861-4cb2-bc33-f6f94c390173" alt="SoilData" width="800px"/>
</p>

  * The data was collected from the EMBRAPA - "Empresa Brasileira de Pesquisa Agropecuária", the Brazilian Agricultural Research Corporation, a state-owned company.


2. **Climate data**

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/50c80e68-817e-48e3-b607-b791e1d3810b" alt="ClimateData" width="500px"/>
</p>

* The data was collected from the INPE - "Instituto Nacional de Pesquisas Espaciais", the Brazilian National Institute for Space Research.

3. **Municipal Agricultural Production - "Produção Agrícola Municipal (PAM)​"**

  * PAM (Municipal Agricultural Production) is an annual survey conducted by IBGE (Brazilian Institute of Geography and Statistics) that provides statistics about agricultural production of 64 products in different regions of Brazil. It covers data such as planted and harvested area, **production**, yield, and price for both temporary and permanent crops at municipal, regional, and national levels.
  * We used **the production, in kg per hectare,** provided by the Municipal Agricultural Production as **the target variable for our regression**.


---


### Our Solution - *Machine Learning*:

For selecting the appropriate machine learning model for the task, we employed **AutoML**, a technique that involves automatically testing various different models. The results can be seen in the table below:

<div align="center">

| Model          | Algorithm Name                    | R2     |
|----------------|-----------------------------------|--------|
| et             | Extra Trees Regressor             | 0.7915 |
| rf             | Random Forest Regressor           | 0.7800 |
| catboost       | CatBoost Regressor                | 0.7585 |
| lightgbm       | Light Gradient Boosting Machine   | 0.7548 |
| xgboost        | Extreme Gradient Boosting         | 0.7497 |
| gbr            | Gradient Boosting Regressor       | 0.6805 |
| knn            | K Neighbors Regressor             | 0.6409 |
| dt             | Decision Tree Regressor           | 0.6034 |
| lar            | Least Angle Regression            | 0.5761 |
| br             | Bayesian Ridge                    | 0.5761 |
| ridge          | Ridge Regression                  | 0.5761 |
| lr             | Linear Regression                 | 0.5761 |
| huber          | Huber Regressor                   | 0.5682 |
| lasso          | Lasso Regression                  | 0.5556 |
| en             | Elastic Net                       | 0.5363 |
| omp            | Orthogonal Matching Pursuit       | 0.5235 |
| ada            | AdaBoost Regressor                | 0.2710 |
| par            | Passive Aggressive Regressor      | 0.1479 |
| llar           | Lasso Least Angle Regression      | -0.0002|
| dummy          | Dummy Regressor                   | -0.0002|

</div>


Afterwards, we employed **Bayesian Otimization with SMAC to optimize the hyperparameters** of the best model (Extra Trees Regressor):


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/d22c0f06-8df8-4c9b-ba7c-332e754a09e3" alt="Bayesian Otimization" width="500px"/>
</p>

The optimized model achieved an R2 score of **0.84**.

---


### Our Solution - *Optimization*:

Based on the productivity and risk data, we applied a two-step optimization process to arrive at the distribution per city:

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/fe8e5a41-e855-490a-9c16-33710c19c84a" alt="Optimization" width="700px"/>
</p>

The genetic algorithm was implemented and is executed as follows:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/1b8e326f-56bd-4134-b7be-b7740febb51a" alt="Genetic Algorithm" width="900px"/>
</p>

1. We commence with the Initial Solution, provided by the intra-optimization in each city (referred to as "Step 1" in the previous figure).
2. Random alterations are made to the Initial Solution, leading to the creation of modified solutions.
3. From the best of these modified solutions, we conduct a "genetic crossover." In other words, we combine elements of various solutions to produce new samples. In the figure, this concept is depicted by new-generation samples possessing mixed "genes" (colors) from the previous generation.
4. From the pool of modified samples and those obtained through crossover, we select those with the highest scores to constitute the new generation.
5. The aforementioned steps are repeatedly executed until the desired convergence is achieved, at which point we adopt the best resulting solution.

---

### Our Solution - *Results*:

Given the value of the percentage of available area to be allocated to each Amazon-compatible product, along with the market values of these products, it is possible to estimate the generated value creation for the region.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/f026f0eb-490e-4a8f-9fae-ad14fdebf9ac" alt="Results" width="600px"/>
</p>


---

### Our Solution - *Consulting*:

To ensure the feasibility of our solution, it's crucial to unite the three key stakeholders. Their combined expertise, insights, and resources will be instrumental in navigating the challenges and intricacies of the project:

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/1a11875e-7172-4ca1-924f-d0cc1bc6b510" alt="Consulting" width="800px"/>
</p>

---

### Our Solution - *Social, Environmental, and Economic Consequences*:

We believe in refining existing social initiatives, optimizing agricultural practices per municipality, and promoting eco-friendly monitoring to preserve our forests. Furthermore, our solution has focus on polyculture and native cultivation aims to enhance biodiversity while also bolstering familial agricultural output by minimizing risks:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/4c54ad0e-c68a-4abf-aafa-0337fd58c3bb" alt="Consulting" width="650px"/>
</p>

### Our Solution - *Conclusion*:
Our solution enhances existing social programs by using **machine learning** and **genetic algorithms** to align harvests with a municipality's planting preferences. We adopt organic methods to protect our forests and champion the cultivation of native crops. Our goal is not only to increase agricultural yield for families and mitigate risks but also to sustainably drive economic prosperity in the region. Collectively, these initiatives bring about notable social, environmental, and economic advantages.

## Acknowledgements

We'd like to sincerely thank the BCG team for giving us this opportunity. The challenge of addressing such a pressing issue, vital for Brazil, Latin America, and the global fight against the climate crisis, is deeply appreciated.

## Contacts

If you appreciated this project, wish to discuss it further, or have suggestions, ideas, or feedback, we would be honored to hear from you. Your perspective could be invaluable in refining our approaches and making an even greater impact. Please do not hesitate to reach out to us. We are always open to dialogue and collaboration.

