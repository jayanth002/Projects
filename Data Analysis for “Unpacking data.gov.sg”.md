# Data Analysis for “Unpacking data.gov.sg” Research Project under Prof. Hallam Stevens at NTU University.

**1 Introduction**
The open data framework is a boon for the citizens, researchers and policy makers to redefine the
model of governance and innovation. Not surprisingly, the Singapore open data
portal(https://data.gov.sg/), has lot to offer to the information seekers. The data in the portal is
subdivided into 9 categories such as economy, education, environment, finance, health,
infrastructure, society, technology and transport. The purpose of the research is to evaluate the core
parameters about the formation of the data in the Singapore Data Portal and its results.

**2 Research Questions**
To address the fundamental core of a research project, the following questions are reproduced to
determine the approach to analyze and report the outcome.
- How much data is there? How many datasets? What is the size of each?
- How is the data categorized?
- How much data is there in each category?
- What are the sources of the data?
- How much data comes from each source?
- What topics does the data cover according to the keyword analysis?

**3 Methodology**
**3.1 Dataset Collection and Characteristics**
The several datasets are positioned in each category in the data portal, while among the data
elements in each category, the “About this dataset” element covers most of the research questions,
respectively. The respective elements are extracted using different form of technique includes using
third party tool, python source language and data cleansing. The Table 1 describes the original data
element exist in the Singapore government open data portal, while the extracted element is
formatted as in Table 2. 

![image](https://github.com/jayanth002/Projects/assets/32224793/be86b179-1583-417a-9f5c-eb310928f9a4)


![image](https://github.com/jayanth002/Projects/assets/32224793/b18e1321-7f05-4872-92a7-e2355a84b6ab)


**3.2 Data Preprocessing**
Further to analyze the extracted element, the R programming language has been executed to analyze
the word frequency and associated terms. In this process of determining the accurate word frequency
in each category of the data, the following data preprocessing actions has been performed such as
conversion of the text to lower case and exclusion of the numbers, stop words, punctuations and extra
white spaces, respectively (shown below Table 3-7). Additionally, apart from other packages to
perform the operation including the word cloud formation, the tm- text mining package has been a
main source of performing the operation including the formation of term document matrix. 

![image](https://github.com/jayanth002/Projects/assets/32224793/1de2b932-ce57-40e3-9260-542c0f6a1d35)

**4 Analysis**
This section provides insights about the patterns involved in both individual and consolidated data,
respectively.

**4.1 Individual Category**
This subsection provides pattern involved in the data for each category such as education,
environment, finance, technology, transport, economy, health, infrastructure and society. Further the
keyword analysis for each category is covered under Appendix A.

**4.1.1 Economy**
The term “economy” is associated with many aspects including the production and consumption of
materials and services and the cash flow. Refering to Appendix A- Fig 1, in summary, the keyword –
data and survey are more prominently exists in the dataset description about the economic aspects
of the Singapore region. Appendix A – Fig 2, provides the visualization of the Word Cloud of the
economy dataset. Further more, Appendix A – Fig 3, portray information about associated terms to
word – survey. The survey method has been predominatly employed to obtain necessary information
about the economic prospects of the country. The wide range of surveys has been executed such as

- Annual survey to gather information about the structure and the performance of the sectors
including retail, transport, health services, etc.
- Business expectation survery to obtain immediate future of the firms in the services sector.
- Labour Market Survey to estimate the job vacancies, redundant positions, employee strength
in the company of atleast 25 employees,etc.
- Labour force survey to provides insights about the employment change in the industry,
percentage of employed and unemployed workforce, etc.
- Survey of financial structure and operations of the companies to estimate the equity ratio,
liquidity, etc., of the companies.
- Survey of foreign equity investment and foreign debt and financial derivatives transactions
to calculate the return on the foreign direct investment.
- Survey of Singapores investment abroad to calculate the percentage of Singapore investor in
the overseas enterprise.
- Etc. 

**4.1.2 Education**
The education system in Singapore has 4 core stages such as Pre-School, Primary, Secondary and Post
Secondary. The Pre-School education is managed by MOE Kindergartens for the four to six years old
chidren. The Primary school is a compulsory 6 years education, which upon completion, the students
are entitled to Primary School Leaving Examination (PSLE) to further upscale to secondary
education. The Secondary school range for about 4 – 5 years. The GCE level examination on other hand
necessitates to upscale to the post-secondary education. For more information on education
hierarchy, please refer to MOE website at https://www.moe.gov.sg/education/education-system.
As per the Appendix A – Fig 4 and 5, the keyword students remain most frequently in the education
datasets, followed by words such as courses, school, offered, enrolment, etc. In addition, as per the
Appendix A – Fig 6, subjects remain the top associated term to the keyword students, followed by
potential terms such as primary, o level, etc.
Refering to the keywords and the associated terms,in summary, the datasets in education category
describe key information as follows:
- Performance of the students in the national level exams such as PSLE and GCE.
- Available courses, enrolment figures, etc in kindergartens, primary, secondary and in
teritiary institutions.
- Student and teacher ratio.
- School directory information about all schools.
- Etc. 

**4.1.3 Environment**
The necessary environment related information is captured in the Singapore open data portal.
Referring to the datasets, as per the Appendix A – Fig 7 and 8, the most frequent word remains to be
waste. Furthermore, as per the Appendix A – Fig 9 the associated terms to the word waste such as
landfilled, tonnes, generated, etc., covers under the statistics of the solid waste management in the
datasets.
The below key information about the environment datasets is summarised as follows:
- ABC(Active, Beautiful, Clean) Waters Programme is an initiative developed by the
government to produce the clear rivers, streams and lakes to the community.
- Cash-For-Trash Programme is an initiative by the Public Waster collectors to exchange
recyclable items for the currency at the deputed recyclable stations.
- Validation of air quality by measuring the pollutant levels.
- Estimate the effects of climate change and energy. 

- Validate the electricity generated and its consumption.
- Licensed food establishments.
- Historical weather conditions.
- Solid Waste Management,etc.

**4.1.4 Finance**
In overview, the Singapore financial system is stable with the wide range of accessibility to the
global markets and well planned financial architecture. Most prominently, Singapore remains hub
for most of the financial markets in Asia.Further as per the financial datasets, the frequent words in
Appendix A – Fig 10 and 11 appears to be year, tax, income, etc. and the associated terms in Appendix
A – Fig 12 refers to assessment, period, income, tax etc. Referring to the frequent words and the
associated terms, the key points from the datasets are summarised as follows:
- Collection of the taxes and Tax rates.
- Baby Bonus Scheme - The Child Development Co-Savings scheme to diminish the costs
associated to raise children.
- Baby Bonus Approved Institution is an entity,which provides service into different service
categories including child centre.
- Information about Dutry Rate, Exchange Rates, GST registered business, loans, etc. 

**4.1.5 Health**
As per the financial datasets, the frequent words in Appendix A – Fig 13 and 14 appears to be
number,singapore,health, etc. and the associated terms in Appendix A – Fig 15 refers to private,
policy holder, practice, etc. Referring to the frequent words and the associated terms, the key points
from the datasets are summarised as follows:
- Incidence rate of different type of diseases.
- Claims under Medishield.Medishield Life is a life long insurance programme for the citizens
and Permanent residents.
- Information about Eldershield policy holders.ElderShield is a severe disability insurance
scheme, which provides monthly cash payout to the policy holder for the certain duration.
- Attendance rate at different health care institutions.
- Location of health care institutions.
- Surveys on the health related events.
- List about the health care providers.
- Information about Zika cluster. Zika is a virus caused through the mosquito infection.
- Etc.

**4.1.6 Infrastructure**
As per the infrastructure category datasets, the frequent words in Appendix A – Fig 16and 17
appears to be indicative, area, polygon, etc. and the associated terms in Appendix A – Fig 18 refers to
polygon, boundary, etc. Referring to the frequent words and the associated terms, the key points
from the datasets are summarised as follows:
- Geographical location of the properties in singapore.
- Government approval on the properties.
- Directory of Government approval, price, booking,stocking and vacancy of the properties. 

- JTC incorporated properties.JTC Corporation - the leading real estate company, which plans,
promotes and develops the industrial landscape.
- Master Plan(MP) - “Master plan is the statutory land use plan, which shows the
permissible land use and the density for the expansion of business in singapore.”
- Control Plans(MP SDCP) - "The Master plan is supported by Special and detailed control
plans(SDCP) . The SDCP are development control plans, which include Parks and
Waterbodies, Landed Housing Areas, Street Block, Envelop Control, Building Height and
Urban Design plans, published by the competent authority."
- Sample Household Survery,etc. 

**4.1.7 Society**
As per the society category datasets, the frequent words in Appendix A – Fig 19and 20 appears to be
population, household, survey, etc. and the associated terms in Appendix A – Fig 21 refers to
censuses, area, distribution, etc. Referring to the frequent words and the associated terms, the key
points from the datasets are summarised as follows:
- Population, birth and death rate
- Annulment of marriage
- Average monthly houshold expenditure
- Average monthly household income.
- Recreation centers in Singapore.
- Marriage and divorce rate.
- Median age group.
- Infringement and detention.
- Resident households.
- Resident population aged 15 years and above.
- Resident students.
- Workforce and unemployment rate.
- Singapore Residents.
- Etc. 

**4.1.8 Technology**
As per the technology category datasets, the frequent words in Appendix A – Fig 22and 23 appears
to be infocomm,statistics,survey, etc. and the associated terms in Appendix A – Fig 24 refers to
survey, individual, research, etc. Referring to the frequent words and the associated terms, the key
points from the datasets are summarised as follows:
- 3G mobile services
- Average monthly household electricity consumption
- Broadband and Mobile data usage
- Computer accessibility
- Scope of Research and Development
- Revenue, expenditure, employment in infocomm industry,etc. 

**4.1.9 Transport**
As per the transport category datasets, the frequent words in Appendix A – Fig 25 and 26 appears to
be vehicles,registered,road etc. and the associated terms in Appendix A – Fig 27 refers to goods, fuel, tax etc. Referring to the frequent words and the associated terms, the key points from the datasets
are summarised as follows:
- Distribution of vehicles.
- Vehicle parking availability and the rates
- Road and Air accidents reports
- Structure of transport fares
- Rail, road and cycling path layout
- Distribution of road,rail and air ridership 

**4.2 Consolidated Data – Sub element**
The extracted subelements in each of the 9 categories are as follows: managed by, coverage, frequency,
source, format and datasize.Those subelements provides required reference information to the
respective datasets. Further, the statistics on frequency of the subelements has been collected.
Referring to the Appendix B – Fig 1 and 4, both the source of information and the authority,who
manages the section, remain parallel mostly about 99.95%. Those 0.05 % constitute additional
sources. Additionally, the “Ministry of Trade and Industry – Department of Statistics,” remains to be
the top most position among the list in the scope of managing the distribution of Singapore Resident
Population.
As per the Appendix B - Fig 2, most of the datasets donot have the information about the coverage,
while there is no link towards the term period to ascertain the unavailable coverage part. Further
according to the Appendix B – Fig 3 and 5, most of the datasets are in csv format and the frequency
of data updation remains to be annually. Lastly, with reference to Appendix B - Fig 6, the file size for
the dataset “Information on Corporate Entities,” regulated by Accounting and Corporate Regulatory
Authority, reamins to be highest with abot 760 MB of data. 

**5 Conclusion**
In summary, this report covered most of the research questions pertinent to the Singapore
Government Open Data Portal. In this process, the collected data has been visualised for the ease of
representation.Additionally, the key points of the datasets for each category have been depicted.
Further the challenge has been encountered to address the representation of each dataset as per the
research question due to the complexity of extracting the particular element. In total, the required
data have been protrayed with statistics for the interpretation about the organisation of the
information in the Singapore open data portal. 

**6 Appendices**
**6.1 Appendix A – List of figures about the statistics of frequency of the words and the associated terms**

**Economy**

![image](https://github.com/jayanth002/Projects/assets/32224793/420395aa-2813-47c0-844c-04b3704b1292)

![image](https://github.com/jayanth002/Projects/assets/32224793/a61829bd-504f-4976-8991-a10fd3fd680a)

![image](https://github.com/jayanth002/Projects/assets/32224793/1c11e4fd-6948-4777-802d-076e57f14eac)

**Education**

![image](https://github.com/jayanth002/Projects/assets/32224793/83d4d4c8-66ab-40e0-a9ee-b143472e2de0)

![image](https://github.com/jayanth002/Projects/assets/32224793/6052c489-7927-4b86-af2a-e8d58cb20524)

![image](https://github.com/jayanth002/Projects/assets/32224793/8224bd09-3ee8-41f3-bd7f-02dd111e9882)


**Environment**

![image](https://github.com/jayanth002/Projects/assets/32224793/10e08acc-70b8-476e-9469-7cc0ddf90740)

