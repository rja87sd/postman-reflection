# postman-reflection
Week 5 Assignment Repository

## Day 1 Assignment
In Postman, the API shows the name of the Pokemon, a list of its abilities, whether or not the abilities are hidden, and a list of other statistics like which game the Pokemon appeared in and its Pokedex number as of that game, what moves it can learn and what level it can unlock them at. It shows all of this in JSON format, making it easy to retrieve the data as needed by the application. There are even different text formats available to the user in Postman, like Pretty, Raw, etc. I chose Charmander, Charmeleon, and Charizard because dragons are my favorite type of fictional creature.
- 1: Charmander ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/b0245f87-83e6-43b4-8bd5-3cd958fe097b)
- 2: Charmeleon ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/b3c23584-d331-4c2d-8c83-3689e26da249)
- 3: Charizard ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/c473d1eb-8614-43e9-b2a1-cf686ce916dd)


## Day 2 Assignment
Screenshots:
- Date and Time
  ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/a9822e53-3fa4-452a-a027-f858e799a877)
- Min, Max, and Average Humidity
  ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/0e3cf60f-1b95-4354-96a8-1ff87c16b71d)
- Min, Max, and Average Temperatures
  ![image](https://github.com/rja87sd/postman-reflection/assets/145504216/666adb70-525b-4710-b7d8-dd8b1bbf6534)

- On Query Parameters:
  It's important to have the correct query parameters in order to request the data you want or have it organized in the way you want. Case in point, it took me a while to find the right parameters to have temperatures shown in Imperial units (Fahrenheit). By default all temperatures were shown in Metric (Celsius). It is also important to note that entering the wrong parameters can result in an error. While figuring out how to request only daily forecasts, I got an error saying that the query parameters I'd entered were not valid. (screenshot below). Note the timesteps value is set to 7d. I was trying to get a 7-day forecast, but was requesting in the wrong format. In order to get a daily forecast, I had to enter 1d in timesteps.

![image](https://github.com/rja87sd/postman-reflection/assets/145504216/6120949a-baf5-4b1d-9897-cb1d70d7a801)


## Day 3 Assignment
- Create an Environment for the Weather API.
-- From the My Workspace tab, click on Environments in the lefthand sidebar.
-- Click the + sign above Globals.
-- Change the name of the New Environment to 'Weather API Environment'.
![image](https://github.com/rja87sd/postman-reflection/assets/145504216/dc644443-a662-4755-a25d-8409d533c01b)

-Add a variable for the API key, e.g., name it weatherApiKey.
-- In the Weather API Environment tab, click in the text field under 'Variable' and type in 'weatherApiKey'.
-- Under 'Type', click the dropdown box and select 'secret'.
-- Under 'Initial Value', click the empty text field and paste your API Key value.
-- Under 'Current Value', click the empty text field. It should automatically populate with hidden text representing your API Key. If not, paste your API Key into the text field.
-- Click 'Save'.
![image](https://github.com/rja87sd/postman-reflection/assets/145504216/5a5302a2-1fd2-4636-9ab6-0c993adfada7)

- Create a new request in the "Weather API Collection".
-- Click 'Collections' in the lefthand sidebar.
-- Click the + sign up at the top, just under 'My Workspace'.
-- Rename the new Collection.
-- In the sidebar, click the Collection name and click the three dots to bring up a menu of actions.
-- Click 'Add Request'.
-- Rename the new Request.
  
- Use the environment variable for the API key in the request.
-- Ensure the Weather API Environment is selected as the active environment by clicking the dropdown menu in the top right of the screen.
-- Click 'Weather API Environment'.
-- Input the key 'apikey' with value '{{weatherApiKey}}'
  
- Choose an endpoint provided by the weather API and set necessary parameters, such as location.
-- Set 'location', 'timesteps', 'units', 'timezone' keys with their respective values.
-- Click 'Send'.

![image](https://github.com/rja87sd/postman-reflection/assets/145504216/24102cbc-4cce-4353-a4a8-409a6c73d269)


