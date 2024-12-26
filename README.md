# Optimal Shop Location

Some time ago, we went shopping. After discussing with a furniture and decor shop owner their reason for closing their shop and putting their 
remaining inventory on sale, we found that the shop owner believed they'd not picked the best or most optimal location for their shop. 
Sales  had been rather slow; so they were closing the shop and moving it to a location that they had concluded would be 
more ideal for the furniture shop, given the price range of the items and the shoppers' preferences.

What if the shop owner had made the correct analysis and placed their shop in the more optimal location? 
That would have saved them money and time. 

This inspired a project that would determine the optimal location for a shop, given all the possible variables that go
into such determination: income, demographics, distance to shoppers and clientele, etc. Expectedly, small shop owners use rule
of thumb and intuition, and experience and some sales data to determine where to locate their next shop. And giant multi-national shops have analysts using data 
and algorithms to help inform and determine shop locations.

This open-source (MIT License) project intends to replicate the data analysis and algorithmic processes that 
help inform shop locations. For starters, determining shop location demands some economics and econometrics, with some help from
machine learning. We look forward to sharing the data and code as we research and implement the application. 


# Literature Review

Quite a bit of research has been conducted on optimal shop location. We would expect most big retailers to have even more 
detailed and comprehensive models and data sets for their research and decision making. Here, we list some of the research 
to get us started.

1. Competitive location models: A review https://www.sciencedirect.com/science/article/pii/S0377221723008056
2. Is Location a competitive advantage on retail convenience shopping?: https://www.researchgate.net/profile/Kezia-Mkwizu-2/publication/332182678_Is_Location_a_competitive_advantage_on_retail_convenience_shopping/links/5ca51355299bf1b86d633235/Is-Location-a-competitive-advantage-on-retail-convenience-shopping.pdf
2. DeepStore: An Interaction-Aware Wide&Deep Model for Store Site Recommendation With Attentional Spatial Embeddings: https://hal.science/hal-03363389/file/3447271.pdf
3. Intelligent site selection for bricks-and-mortar stores: https://www.emerald.com/insight/content/doi/10.1108/mscra-03-2019-0010/full/pdf
4. Store Location Selection via Mining Search Query Logs of Baidu Maps: https://arxiv.org/pdf/1606.03662
5. MetaStore: a task-adaptative meta-learning model for optimal store placement with multi-city knowledge transfer: https://hal.science/hal-03363389/file/3447271.pdf
6. Applied Retail Location Models Using Spatial Interaction Tools: https://www.researchgate.net/profile/Morton-Okelly-2/publication/263389703_Applied_retail_location_models_using_spatial_interaction_tools/links/5413ac410cf2bb7347db266c/Applied-retail-location-models-using-spatial-interaction-tools.pdf
7. A Review of Selected Factors Conditioning Consumer Travel Behavior: https://www.researchgate.net/profile/Raymond-Hubbard/publication/24099266_A_Review_of_Selected_Factors_Conditioning_Consumer_Travel_Behavior/links/56a01f9e08ae21a564274024/A-Review-of-Selected-Factors-Conditioning-Consumer-Travel-Behavior.pdf
8. Store location with multipurpose shopping trips and a new random utility customers’ choice model: https://ideas.repec.org/a/eee/ejores/v305y2023i2p708-721.html
9. Location and Agglomeration: The Distribution of Retail and Food Businesses in Dense Urban Environments: https://www.researchgate.net/profile/Andres-Sevtsuk/publication/280218425_Location_and_Agglomeration_The_Distribution_of_Retail_and_Food_Businesses_in_Dense_Urban_Environments/links/58c6a34b92851c0ccbff6c1e/Location-and-Agglomeration-The-Distribution-of-Retail-and-Food-Businesses-in-Dense-Urban-Environments.pdf
10. AR2Net: An Attentive Neural Approach for Business Location Selection with Satellite Data and Urban Data: https://dl.acm.org/doi/abs/10.1145/3372406
11. Identifcation of robust retailing location patterns with complex network approaches: https://link.springer.com/content/pdf/10.1007/s40747-021-00335-8.pdf


# Data

At minimum, we would need retailer and consumer data, as well as some location data for such analysis. We found some publicly available data to get us started: 

1. Kaggle Consumer Behavior and Shopping Habits Dataset: https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset
2. Kaggle Retail Data Analytics: https://www.kaggle.com/datasets/manjeetsingh/retaildataset
2. Foursquare Open Source Places: A new foundational dataset for the geospatial community: https://location.foursquare.com/resources/blog/products/foursquare-open-source-places-a-new-foundational-dataset-for-the-geospatial-community/
3. Data.gov Grocery Store Locations (Washington, DC) : https://catalog.data.gov/dataset/grocery-store-locations
4. Data.gov Warehouse and Retail Sales: https://catalog.data.gov/dataset/warehouse-and-retail-sales
5. Data.gov Quarterly Retail Sales Tax Data by County and City (Iowa): https://catalog.data.gov/dataset/quarterly-retail-sales-tax-data-by-county-and-city
4. AWS Marketplace Places Data for Retail, Location & Marketing - Free Sample: https://aws.amazon.com/marketplace/pp/prodview-uheekokilsn5k#offers
5. Consumer Behavior and Shopping Habits Dataset: https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset
6. Datarade Best Retail Datasets for Retail Market Research (some are paid but there are free samples):https://datarade.ai/search/products/retail-datasets
7. AWS Retail, Location & Marketing Data: https://aws.amazon.com/marketplace/search/results?category=2d1c8868-2642-4741-af5d-9ced77da7024&FULFILLMENT_OPTION_TYPE=DATA_EXCHANGE&filters=FULFILLMENT_OPTION_TYPE
8. Data.gov Warehouse and Retail Sales: 
9. Retail trade, trends of seasonally adjusted sales, Canada by retail trade sector, inactive: https://open.canada.ca/data/en/dataset/00280a6a-48d8-4b99-9a44-e4ceed819a58
10. Leading sources of inspiration for online shoppers worldwide in 2024: https://www.statista.com/statistics/1034149/online-shoppers-sources-of-inspiration/
11. Number of retail store closures in the United Kingdom from 2018 to 2024: https://www.statista.com/statistics/1356731/retail-store-closures-uk/
12. Data.gov Retail Food Stores: https://catalog.data.gov/dataset/retail-food-stores


