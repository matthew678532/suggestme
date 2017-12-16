# suggestme

## Outline

This is a brainstorm for an application which collects a users location data, and provides various activities local to the user within the United Kingdom.

The thought process is that several apis shall be interrogated, to gather data relating to:

- the cinema & the theatre
- local events & festivals
- food & drink places
- nightlife
- shopping centres
- national parks

## Possible APIs

- UK cinema listing API (http://www.cinelist.co.uk/)
- Large cinema listing API (https://developer.movieglu.com)
- Fandangos APIs (Inc cinemas, theatres, etc https://developer.fandango.com/Fandango)
- London Theatre Direct API (https://developer.londontheatredirect.com/documentation/api/inventory-api/introduction)
- Songkick live music events (https://www.songkick.com/developer)
- Eventful, an events API from concerts to sports events (http://api.eventful.com/)
- The List, an events API specifying events within the UK (https://www.list.co.uk/about/events-data/)
- Skiddle, a list of events within the UK (https://www.skiddle.com/api/)
- Google Places API (https://developers.google.com/places/web-service/)
- Food API (https://developers.zomato.com/api)
- Foursquare (https://developer.foursquare.com/docs/api/getting-started)
- National Park Service (https://www.nps.gov/subjects/developer/api-documentation.htm)

## Architecture

Due to the size of the application, and the likely complexities that will be encountered during development, the application will be need to be separated into layers. One layer will handle the business logic of the application, and the other layer will handle user inputs and requests.

To accomodate for these layers, a RESTful api is to be developed to handle the business logic, and a web application is to be developed to handle user requests.

However, through implementing a RESTful api, the development of applications can be cross-platform (iOS, Android, etc). Therefore, future developments may include builds for these platforms.

## Technologies and Tooling

The technologies and tools I want to utilise within this project are as follows:

### Technologies

- Continous Integration, and Deployment
- Version Control Systems
- RESTful APIs (inc API Documentation)
- Web Applications (Client Implementations)
- Build Systems
- Package Management
- Databases (Hosted Solution)
- Encryption / Security
- Testing (Code Quality)
- Design Patterns

### Tooling

- CircleCI
- Git (Github as the Cloud Hosted Service)
- NodeJS (Restify as the API Development Framework)
- React, Sass (SCSS Syntax), JS (ES6), NodeJS
- Gulp (API), Webpack (Web App)
- NPM
- MongoDB Solution (Possibly mLab/Easy to parse)
- OAuth for User Accounts / HTTPS for API Endpoints
- Mocha with Chai (API), Jest & Enzyme (Web App)
- 3 Tier Architecture (API), MVC (Web App)

## Documentation Resources

**_Todo.._**
