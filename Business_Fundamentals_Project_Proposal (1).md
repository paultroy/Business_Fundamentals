What is the framing question of your analysis, or the purpose of the model/system you plan to build?
+ Hypothetical scenario: As an attempt to increase driver safety and reduce traffic caused by accidents, Google Maps wants to create a new feature that provides a safety rating prediction for the driving route based on the start and end locations inputted by the user.

+ Framing Question: Is there a way to quantify/classify the safety of a driving route? If so, what features are used to calculate said safety score?

Who benefits from exploring this question or building this model/system?
+ Google Maps as a company benefits from this analysis because it helps the provide information they can use during development of their new product. Additionally, successfully creating this product would ideally reduce the number of car accidents, thereby increasing driver/public safety and reducing traffic time for other drivers not involved in the accident.

Data Description:

What dataset(s) do you plan to use, and how will you obtain the data?

I plan to start with this dataset that's available from city of Denver for free. I may bring in other data sets from Colorado Department of Transportation for things such as highway traffic counts or road type, if time permits.
+ https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-traffic-accidents
    + This data set is for the past 5 years of traffic accidents. For my project, I plan to use only 2021 year to date      data.


What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
+ An individual sample would be one recorded accident. I plan to work with the following features: type of traffic offense (accident vs hit and run), accident date, neighborhood location where accident occurred (use exact lat/lon if time permits), whether bicyclists was involved in accident, whether pedestrian was involved in accident, road condition at time of accident(e.g. dry/wet), light condition at time of accident (e.g. light/dark), general road description (e.g. at intersection, not intersection, highway interchange, etc.), vehicle type, vehicle movement (left turn, right turn, chaning lanes), reported cause of accident (e.g. careless driving), human factor for reported cause (DUI, distracted passenger), serious injury (y/n), fatality (y/n)

If modeling, what will you predict as your target?
+ No initial plans for modeling. Thinking classificaiton model may be usable.

Tools:
How do you intend to meet the tools requirement of the project?
+ I will use Google Sheets to clean my data, perform EDA and create visualizations. I will also use Tableau to visualize my EDA findings.

Are you planning in advance to need or use additional tools beyond those required?
+ No

MVP Goal:
What would a minimum viable product (MVP) look like for this project?
+ Provide a line chart that shows how the number of accidents changes throughout the hours of the day.


```python

```
