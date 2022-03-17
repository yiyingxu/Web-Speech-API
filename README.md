# Web-Speech-API
develop a chatbot web application

Developer Manual
a.	Car navigation system:  Currently, the car navigation system has poorly functioned, which is limited to searching for the destination and presenting the fast route. My project is aimed to create an intelligent application can automatically search nearby attraction areas of a place for the driver.

b.	Web speech API: Web speech API is to make the intelligent application able to interact with uses. When a driver speaks to the application, web speech API could identify and recognize the voice. After that, the web application can also speak to driver by its SpeechSynthesis (transfer from text to speech). Drivers are not able to type during driving, so Web speech API is necessarily.

geolocation API: geolocation API is used to monitor driver's location data and time data; it is sourced from GPS services.

Place API: Place API is used to search the nearby places and returns information about these places; drivers can use the function to search the places they would like to go.

Web crawlings: Web crawlings are used to browse the internet and find information related to attractions and interesting places, it is also used to update the data achieved in the application.

c.	Dialog scripts
User: Hello/Hi.
System: Hello, driver.

User: Show my location.
System: I am checking your location, wait a minute.
And the system will show the latitude and longitude of the user’s location and show them on the map.

User: Please do web crawling for my favorite restaurant website. / or say anything with the key word “crawling”.
System: Will show the content under p tag of the website: https://www.broadsheet.com.au/melbourne/guides/best-restaurants

User: I would like to find the nearest restaurant, please give me more details about restaurant location and type.
System: I am checking the restaurants near your location, wait a minute.
The system will extract the noun phrase from the sentence, and then find the nearest restaurant and send the related information of this restaurant to the user.

User: Recommend some diners/hotels for me.
System will recommend restaurants or hotels for the user based on the preference.

User: I do not like your website. / or say anything with the key word “website”.
System will do opinion mining on the user’s sentence.
If the user is in good mood, system will say: Thanks for using the web application.
If the user is in bad mood, system will say: Please leave a comment.

d.	Natural language processing: using noun phrase extracting to extract key word and then the system will react to different key words.

Opinion mining and sentiment analysis: The system will detect user’s sentiment words and react differently according to the user’s opinion.

Recommendation with user data: The system will give recommendation of a ranked list based on user preferences.

e.	Past user’s data is not included in the project as no prediction are made in the system. The file sample_list.php in the assignment folder record the user’s preference of restaurants and hotels, and the file is used for giving recommendation.

f.	None.

g.	Video link: https://youtu.be/3Qp8wawXl4s
