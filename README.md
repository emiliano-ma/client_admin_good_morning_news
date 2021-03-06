# The Admin Client

[Visit the deployed site](https://goodmorningnews-admin.netlify.app/login)</br>

[![Netlify Status](https://api.netlify.com/api/v1/badges/38456bc3-a77b-46e0-9af3-ac2eacaafe3d/deploy-status)](https://app.netlify.com/sites/good-morningnews-admin/deploys)

The news room challenge: We have built three clients served by one API.
We built a newspaper platform with the user client, the admin client and a user mobile client with React Native.

- [API](https://github.com/emiliano-ma/api_good_morning_news.git)
- [Mobile](https://github.com/emiliano-ma/mobile_good_morning_news)
- [Admin](https://github.com/emiliano-ma/client_admin_good_morning_news)
- [User](https://github.com/emiliano-ma/client_user_good_morning_news.git)

The project extended throughout 3 sprints of one week duration each. We worked in a team of 4 people.

## Built with

**:** React v.16.13.1 </br>
**Testing framework:** Cypress

## Getting started

### Dependencies

- Yarn
- React
- Cypress
- Axios
- Semantic-ui-react / Semantic-ui-css
- React-images-uploading
- React-redux
- J-tockauth

### Setup

After cloning the repository to your local. </br>

```
$ yarn install
```

Start cypress and run the feature tests:

```
$ yarn cy:open
```

Start the React application and run it on your local host:

```
$ yarn start
```

### Login credentials

- Journalist: email: journalist@mail.com password: password

## Updates/Improvements

- Functionalies for an editor to review articles and leave comments for the journalist
- Functionality for an admin to manage access and roles.

## License

[MIT-license](https://en.wikipedia.org/wiki/MIT_License)

### Acknowledgement

- Material provided by [Craft Academy](https://craftacademy.se)
