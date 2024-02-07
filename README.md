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

- On Query Parameters
  It's important to have the correct query parameters in order to request the data you want or have it organized in the way you want. Case in point, it took me a while to find the right parameters to have temperatures shown in Imperial units (Fahrenheit). By default all temperatures were shown in Metric (Celsius). It is also important to note that entering the wrong parameters can result in an error. While figuring out how to request only daily forecasts, I got an error saying that the query parameters I'd entered were not valid. (screenshot below). Note the timesteps value is set to 7d. I was trying to get a 7-day forecast, but was requesting in the wrong format. In order to get a daily forecast, I had to enter 1d in timesteps.

![image](https://github.com/rja87sd/postman-reflection/assets/145504216/548c22d0-0d7a-4147-9c9f-cec056998088)




