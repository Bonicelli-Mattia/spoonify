# Spoonify
This project is the result of a team four-day hackathon realized during the Immersive Program at [Code Chrysalis](https://www.codechrysalis.io/).

## Background
The constraints around this hackathon were the following:
* Build a full-stack app and present it live on Youtube, everything in 4 days.
* Use the industry partner [Stripe](https://stripe.com/docs/api)'s API.

## Youtube video
You can see the event and the presentation at the following link: [Youtube](https://www.youtube.com/watch?v=DHtAGdg5S_4)

## Thanks
Thanks to the team at **Stripe** for the opportunity to work with them during four days, for their support and for taking the time to answer all of our questions.

## Team Members
The team members were as follows:
| Name | Github Handle |
|------|---------------|
| Alix Fachin | [@AlixFachin](https://github.com/AlixFachin) |
| Mattia Bonicelli | [@Bonicelli-Mattia](https://github.com/Bonicelli-Mattia) |
| Jay Sutham | [@jaysutham](https://github.com/jaysutham) |
| Michael Metcalf | [@miachel-metcalf](https://github.com/michael-metcalf) |
| Mark Herring | [@Worldonawire](https://github.com/Worldonawire) |

## Project inception
A lot of small restaurants are impacted by the COVID-19 crisis and have seen their income shrink sizeably, in some cases forcing them to lay off employs to avoid bankruptcy.  
We wanted to provide a platform that helps these businesses survive by diversifying their income streams through selling non-perishable products online.
However, given the time constraint of 4 days we decided to build our MVP around a custom tailored experience for a single customer, to serve as a blueprint and showcase of an average use case.

## Technologies used

* Front-end: `Vue`, `VueX` and `Vuetify`
* Back-end: `Express.js` for our REST API and `knex.js` to connect to our `PostgresQL` database.
* Payments:  [Stripe API](https://stripe.com/docs/api)
* Authentication: [Auth0](https://auth0.com)

## Project setup
We used `npm` as package manager, so if you download our repo (`fork` and `clone`), you can get a development environment ready by following these steps:
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## License
This product is licensed under the MIT License. Please have a look at the [licensing file](LICENSE.md) for more information.
