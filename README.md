# Place Search Challenge

Thanks for taking the time to interview for a position at BeTheSomm! To assess your coding skills, we've designed a coding exercise to be completed on your own as part of the interview process.

The goal of this exercise is to give you the opportunity to demonstrate your coding skills without the pressure of someone watching over you while you work. We respect your time, so please only complete as much as you can in 4 hours and we will continue our discussion should you be selected to come in for an interview.

## Requirements
- Please complete the app in the order of priority. You may not get to all priorities but please complete as much as you could in 4 hours.
- Write the code as if it were going to production. Quality and Unit Tests matters more than the completion of the project
- Please use the [Google places api web service](https://developers.google.com/places/web-service/overview) and not the Google Places android sdk. An API Key will be communicated to you by email so you can use the api for free. This API Key will only be valid for a duration of 15 days
- Except the previous point, You can use any library you want to complete the challenge. 

### Screens Designs

![Screens Design](assets/ui.jpg?raw=true "Screens Design")

### User Story 1
As A user I want to be able to search for a **liquor store** or a **restaurant** I'm interested in by typing the name of the place in a dedicated field so that I can access this place's informations in a Place Details Screen.
- the auto complete suggestions contains the name of the place and its address and only return establishments
- if there is no liquor store or restaurant with the name I typed, I should be displayed that no places matches my criteria
*Hint: You can use the [AutoComplete API](https://developers.google.com/places/web-service/autocomplete)*


### User Story 2
As A user I want to be able to see the detail of the place I searched for by navigating to a place detail screen so that I can have more information about the place I searched.
- The details screen should contain only the name of the place and its address

*Hint: You can use the [Place Details API](https://developers.google.com/places/web-service/details)*

### User Story 3
As a user I want to be able to call the place and visit the website directly from the app so that I don't have to type the number manually in my phone
- The details screen should now contain 2 buttons to call the place or visit the website

### User Story 4
As a user I want to see the last 4 places I searched in the home screen so that I don't have to look for them again.

