**Project description**
A telecommunication company 'TeleCat' wants to know how to predict the customers outflow. To boost customer retentions for such cases it would offer them promo codes and other special conditions. The company's team collected personal data about some customers, as well as the information about the tariffs and contracts they use.

'TeleCat' provides two main types of services:

1. A fixed line telephone connection.
2. Internet connection of two types: via DSL or fiber optic cable.

The following services are also available:

- Internet security: antivirus and harmful websites blocking;
- Dedicated customer support line;
- Data backup cloud storage;
- TV and movie streaming.

Clients can pay for services every month or sign a contract for 1-2 years. Various payment methods and the possibility of receiving an electronic check are available.

**Problem understanding** 
'TeleCat' company has high churn rate and wants to be able to predict customer behaviour in terms of leaving intention

**Project goal** 
Build a model, able to predict customer churn behaviour with ROC AUC score not less than 0.85. 

**Data**
    
The data consists of the following files:
- `contract.csv` - contracts information;
- `personal.csv` - clients personal data;
- `internet.csv` - information about Internet services;
- `phone.csv` - information about telephone services.
Information about contracts is accurate as of February 1, 2020.


**Project content**

- Data loading and preliminary data observation
- Definition of more **elaborate plan**
- Data preprocessing and Exploratory data analysis
- Modeling
- Results communication
