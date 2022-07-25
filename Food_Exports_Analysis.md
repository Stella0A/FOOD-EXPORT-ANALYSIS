# Food Exports Analysis(2004-2019)

# Introduction
This project was one of the case studies I worked on while learning with Utiva, now in 2022 I decided to redo the analysis. 
Its about a pseudo company HiCi Ltd, a local food export company. HiCi Ltd is expanding to the European Union and there are risks of product rejection and detaining of the consignment as reported by the EU Food Safety Standard Agency. HiCi Ltd needs to overcome various regulatory hurdles to be able to penetrate the EU market. The hurdles are border rejection, and mass destruction of substandard product. The dataset contained 514 exports cases and 9 columns which included information about Product_category, Export_year, Notification_type, Risks, Notified_by, Action_taken, Distribution_status, Risk_decision, and Country_of_origin of the products.

![Screenshot (31)](https://user-images.githubusercontent.com/81259955/180771551-88accf0a-a3ac-405f-a3c1-d371448a33f7.png)

# Tools used
Excel, Tableau

# Data Cleaning 
To begin with the analysis, I checked for duplicates and found (62 duplicates) which were removed,changed the inconsistent date format to a same format of dd/mm/yy,removed the null values( if this was a companys dataset, the stakeholders would be notified about the missing values to determine the necessary steps to take). I checked my data validilty and it was ready for analysis so I extracted the cleaned data to a new sheet.

![Screenshot (33)](https://user-images.githubusercontent.com/81259955/180772029-87b61025-686a-45b7-b044-7dc295833abc.png)


# Data Analysis/Visualization

The following are key business questions to be determined:

    a. EU member country that reports the highest number of food rejection. 

Greece reported the highest number of food rejections.

![Screenshot (38)](https://user-images.githubusercontent.com/81259955/180775700-5fdcf86e-06b2-4eb2-b870-0e00db032d06.png)

    b. The most rejected food
The most rejected food is nuts,nuts products and seeds.
    
![Screenshot (39)](https://user-images.githubusercontent.com/81259955/180776235-0ecdeaa1-7b41-4f95-8e1f-6796db647109.png)
    
    c. The country of origin of the most rejected food?
 The country of origing of the most rejected food is Sudan with Nigeria following closely.
    
![Screenshot (42)](https://user-images.githubusercontent.com/81259955/180777255-9e8ef451-6f5d-4a91-83ed-1db74ae0ce10.png)

    d. The most action taken against food exported to the EU?
The most action taken againsts the food products exported to Eu is redispatch of products.
    
![Screenshot (46)](https://user-images.githubusercontent.com/81259955/180777749-182d2ec9-db8b-4868-aaed-b41861b94713.png)

    e. Which of the food products are at the highest risk? 
The food products with the highest risks is nuts,nuts products and seeds with the risks of border control-consigments detained, border control-consigments under customs, food poisoning, company's check, and offical control on the market.

   ![Screenshot (48)](https://user-images.githubusercontent.com/81259955/180778154-5ad23041-e308-4b9c-944d-024b86db0dbb.png)
   
