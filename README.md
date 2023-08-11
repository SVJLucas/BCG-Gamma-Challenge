# BCG Gamma Challenge: How can one promote sustainable economic development in municipalities of the Legal Amazon?

##  BCG GAMMA Challenge Winner

We're proud to announce that our team secured the **First Prize in the BCG GAMMA Challenge for Data Science and Consulting**. This GitHub repository hosts all the code, models, and analytical techniques we employed during the competition.


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/1d278b29-4feb-4a56-87f9-441507fb5a3c" alt="Description of Image" width="400px"/>
</p>


BCG GAMMA, a specialized unit of the Boston Consulting Group (BCG) focused on **Data Analytics and Artificial Intelligence (AI)**, has unveiled its latest initiative: the BCG GAMMA Challenge. **This annual event is designed to spotlight emerging talents in Data Science and offer them a platform to tackle genuine issues**.


## The Challenge

![BCG](https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/141b7f3f-5220-4e4a-aa43-6e088e4b2eb2)


In its fourth edition, **the challenge invites participants to develop analytical solutions that can drive sustainable economic growth in the Amazon Region, in Brazil**. By harnessing publicly available data from local municipalities—ranging from biomes and exports to agricultural production and deforestation—participants are tasked with uncovering vital insights for the area's future.

The challenge centers on promoting sustainable economic development in the municipalities of the Legal Amazon. **Despite the Amazon's vast economic potential, it faces issues such as low social development, underutilized economic opportunities, and increasing deforestation**. Participants are tasked with analyzing data across environmental, social, and economic dimensions using advanced analytics. **The objective is to derive innovative insights and provide actionable recommendations for the Arapyaú Institute, an important local non-profit organization,  or public entities to drive sustainable growth in the region.**

## Our Solution


### Our Solution - *Context: Products compatible with the forest*

**In the Amazon, we​ have a prevalence of monocultures**. Of the entire area planted within its territory in the year 2019:

* 🌱 **55% soybeans**
* 🌽 **27% corn**

These monocultures result in soil exhaustion, leading to the nutritional degradation of the land. On the other hand, only a small percentage of cities (about 3% in the region) utilize *products compatible with the forest*:

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



By not using products compatible with the forest, **these cities are missing out on the global economic potential of these products**:

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/ac52a342-8b6a-4a0c-b8cb-cf9bb0640bf2" alt="Amazon's Participation" width="600px"/>
</p>

### Our Solution - *Context: Social Programs in the Amazon Rainforest*

There are a series of **Brazilian​ Government Social Programs** encouraging production in the Legal Amazon, like:​

* **"Auxílio Inclusão Produtiva Rural"**: It is the granting of a monthly financial aid so that the citizen can start investing in their own rural production. Through this benefit, they will receive training from an agricultural technician on managing small-scale farming.
* **"Fomento Rural"**: The Rural Development Program combines social and productive monitoring with direct financial support for poor rural families to invest in productive projects. The goal is to enhance their food production, income generation, and overall well-being, contributing to improved food security and poverty reduction.
* **"Alimenta Brasil"**: is a food acquisition program that supports access to food and encourages production among various traditional groups. Through streamlined procurement, the government buys food from these groups and distributes it to those in need, including families, schools, health facilities, and correctional institutions.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/b5afae52-9b27-4c64-99a6-44bdf47bc23d" alt="Social Programs" width="400px"/>
</p>

While these programs cover **62%** of the families receiving assistance in the region, **they do not mention products suitable for the Amazon rainforest**. This means that there is encouragement for **agriculture without taking into account the local biome and ecological diversity**.

### Our Solution - *Proposal*:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/4f7b4a46-5d4d-45ab-b996-25e7a0631e38" alt="Proposal" width="500px"/>
</p>

The primary goal is to provide additional incentives to local families to cultivate products that are compatible with the Amazon rainforest biome. Concurrently, the Brazilian federal government should purchase these products from the families and utilize them for the food supply in its facilities, including hospitals, schools, prisons, and the like.

### Our Solution -  *How to select diverse products compatible with the Amazon rainforest that are suitable for the biome and climate of each municipality?*

We selected eleven products with the highest production history and analyzed the last ten years to extract the return and risk per municipality.

**The best strategy for selecting the products will be one that focuses on diversity, promoting biodiversity, meeting diverse nutritional and economic needs of local communities, and helping to reduce the risk associated with each product's harvest.**

The choice should take these factors into consideration, **maximizing the income generated (return) from the investment of the Brazilian Government**:


<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/3c1f057d-df24-42e0-b3a6-e8a01fb5f064" alt="ReturnRisk" width="800px"/>
</p>

### Our Solution -  *How to select diverse products compatible with the Amazon rainforest that are suitable for the biome and climate of each municipality?*

To choose the distribution of products in each city, we propose a solution (pipeline) that combines two techniques:

* **Machine Learning**: Using soil data for each city (pH, salinity, carbon, and saturation) as well as climate data for each city (temperature, rainfall, wind speed), we can generalize a model that can predict the productivity of each of the products compatible with the Amazon rainforest for each city.
* **Metaheuristic Optimization**: Using metaoptimization through a genetic algorithm, given the productivity of each city, we can find the best configuration of products suitable for the biome and climate of each municipality, maximizing the return-profit ratio for the Brazilian government.

<p align="center">
  <img src="https://github.com/SVJLucas/BCG-Gamma-Challenge/assets/60625769/7d21b992-85ff-4638-96c3-5b27d38e0318" alt="ReturnRisk" width="800px"/>
</p>




