## EZ Comps - Your real Estate Buddy
A Rails powered real estate app that allows users to quickly determine the value of their home

### Glossary
* Comp: Short for "comparable home"; has sold in the last 18 months and is located in the same neighborhood as the home in question. Provides sales data which can help determine the value of a home
* Zestimate: Zillow's estimate of what a home is worth based on market trends
* Zester: Ruby gem which facilitates a connection between Zillow's API and a Ruby developer's program
* ERB: Embedded Ruby - a way for Rails to render HTML with functional components

### Technologies
* Ruby on Rails
* Zillow API via the Zester gem
* Google Streetview API
* PostgreSQL
* ERB
* CSS

## Project Description

##### Overview:
This project focused on analyzing the asking price of a house and comparing it to a list of comparable homes received from Zillow's API. A user can search for a home's address, view it's main listing image, see basic info like number of bedrooms and bathrooms, and generate a report on that home if desired. On the report page, a user can see if the home is smaller or larger, cheaper or more expensive, and save the home to favorites.

##### Challenges:
This was one of our first projects so we had not yet learned certain front end frameworks that would have drastically improved UX, such as React, Angular, or Vue. Because of that, this is not a true single-page application. Additionally, the amount of data that we could legally obtain from Zillow was limited, so the accuracy of the reports is highly dependent on the amount of information available for any given property. We used Ruby's built-in exception handling to control how pages are rendered based on available data.

## TODO 
* Refactor with React or similar framework to improve performance
* Convert backend to render JSON rather than ERB so that data can be used by a JavaScript framework
* Allow users to input their own purchase price for the home before generating a report, since offers can differ from asking price

2019 (c) Alex Farmer, Pavel Ilin, Austin Smith
