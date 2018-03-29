# Current-Weather-Analysis
This is Python project which analyse the current weather data and help to understand the weather condition over the glob.
First Identify the open web APIs from the pools of open API available over the internet.
A single API that was chosen for this project was that provided by https://openweathermap.org/
To see this API we need to register first which allows us to get the free 60 day trial. This API has the many option I choose by Zip code option. 
After signing up, I got a API key which I have used to get the current weather data on the basis of zip code and country code.
I have taken the two data set from the current weather records API. 
The first dataset is fetched on 23th march 2018 and the second is fetched day after i.e. 24th March 2018. 
I have used these 2 data set to compare the weather change happen over the one day time period according to the parameters. 
My primary analysis is based on the weather condition in the countries present in the dataset. 
First, I have split the countries by the Equator line which divides the the countries geographally into 2 main parts 
which are Northen hemisphare and southern hemisphare. Northern Hemisphare has US and India and located above the Equator line. 
Southern Hemisphare has Australia and New Zeland located below the Equator line. To avoid the local parameters interferance,
I have analysed the counties of the same Hemispahre first. And then compare both the hemisphare countries on the same parameters. 
As, my first 2 analysis is to compare the weather parameters of one day before and after the data recorded.
And my remaining analysis is based on how parameters changes cause diffrent weather condition overs the diffrent geographical regions.
Last analysis is the percentage of the weather type recorded for all the countries. 
In all my analysis I have obesered that weather type is closely related to wind speed, temperature, Cloudiness and Humidity percentage.
As if the cloudiness and wind speed (on surface) are high but humidity is low then there might be good chance of getting rain fall. 
So I found these parameters closly connected for weather type. Whereas, the visibility is more dependent on Cloudiness as if 
Cloudiness percentage is high, visibility will be high and vice versa. On the other hand, I have obesered how the Equator lines 
plays a vital role in weather condition world wide. And how even in the same Hemisphare, coutries shown diffrent weather condition 
due to underlying parameters on the top of their native parameters. Besides, the Estern counties which are in Southern Hemisphare 
got the early sun rise and sun set whereas Northen hemisphare Western countries got late sun rise and sunset. 
Lastly, the clouds weather is the highest type of weather in all around the countries.

This whole analysis with the explaination is given in the ipython notebook. Cells contains the codes and markdown has all the detailed comments
explaination. To use this project for your own analysis download or clon from my account and import the necessary Python libraries mentioned
in the first cell of the notebook.
My advice is to use Jupyter notebook which has very intarctive and intuitive UI and gives a lot of functionalites for showing your comments.
If you want to run it as a script, copy the code into some editor like notepad++ or sublime text and remove the commant and make sure that
indentation is still maintained. if not, please set the proper indentation before running or compiling the code.
If you dont have API key or wanted to use this on your local stored file then ignore the second and third cell where I have wrote the 
function to create the csv file and load and parse the API JSON data into csv file.
Use the code from the 4th cell where I loading the csv file into Pandas and run the futher code on Pandas data frame.

Thanks!!!
Cheers!!!
If need any help write me at prateekshrivastav786@gmail.com
