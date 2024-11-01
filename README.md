# Scraping_Avito
An integrated web scraping solution for Avito’s real estate section, designed with GDPR compliance in mind to avoid collecting personal information. This project serves as an educational challenge for an introduction to data engineering.
 ![image](https://github.com/user-attachments/assets/efe15ffa-8004-4ee0-a62f-cb09aec8f6de)

### Project Goals
The main goal of this project is educational, aimed at helping users gain familiarity with Python and popular frameworks like Pandas and Selenium.

#### GDPR Compliance
This project complies with GDPR (Règlement Général sur la Protection des Données) by utilizing ethical scraping practices and respecting user privacy. No personal information is collected.

#### Prerequisites and Setup
To run this project, ensure the following technical requirements are met:

Python: 3.13.0
Required Libraries: Selenium, Pandas, Numpy, and Jupyter
Installation
Install the required packages using the following command:

bash
Copier le code
pip install jupyter selenium pandas numpy
Project Setup
Clone the repository:
bash
Copier le code
git clone https://github.com/your-username/Scraping_Avito.git
Navigate to the project directory:
bash
Copier le code
cd Scraping_Avito
###### Install the dependencies as outlined above.
### Error Handling and Logging
The project includes specific error handling for robust execution:

##### TimeoutException: Raised when WebDriverWait cannot find an element within the specified time.
##### NoSuchElementException: Raised if an element cannot be located, returning "NON SPÉCIFIÉ."
##### ElementClickInterceptedException: Raised if a button is intercepted and cannot be clicked.
These exceptions ensure the program runs smoothly, with each handled appropriately to enhance stability.

### Optimization Strategies
Two scraping approaches are provided:

##### User-Agent Simulation: Mimics natural user behavior for stealthier scraping at a slower pace.
##### Fast Data Collection: Optimized for speed to collect data quickly, though with an increased chance of detection.
#### Resources
For more in-depth information, consult the Selenium documentation.

#### Conclusion
This project complies with GDPR regulations and is strictly for educational use only, with no support for malicious purposes.

