# Telecom 
Telecom operator wants to learn how to predict the outflow of customers. If it turns out that the user intends to leave him, promotional codes and special conditions will be offered. The operator's team collected personal data about some customers, information about their tariffs and contracts.

### Description of services
The operator provides two main types of services:
1. Fixed telephone connection. It is possible to connect a telephone set to several lines at the same time.
2. Internet. Connection can be of two types: digital subscriber line (*DSL*) or fiber optic cable (*Fiber optic*).

The following services are also available:

- Internet security: antivirus (*DeviceProtection*) and blocking of unsafe sites (*OnlineSecurity*);
- Dedicated technical support line (*TechSupport*);
- Cloud file storage for data backup (*OnlineBackup*);
- Streaming TV (*StreamingTV*) and movie catalog (*StreamingMovies*).

Clients can pay for services every month or sign a contract for 1-2 years. Various payment methods and the possibility of receiving an electronic check are available.

### Description of data

The data consists of files obtained from various sources:

- `contract.csv` - information about the contract;
- `personal.csv` — client's personal data;
- `internet.csv` - information about Internet services;
- `phone.csv` — information about telephony services.

In all files, the `customerID` column contains the customer ID.

Information on contracts is current as of February 1, 2020.

# Libraries used:
Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn, CatBoost, LightGBM
