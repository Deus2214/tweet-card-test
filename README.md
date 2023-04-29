Tweets project.
Description
The application consist from Home and Tweets pages. Home page is page for welcome and general information. The Tweets page loads user cards from the database. By clicking on the Follow or Following buttons in the card, you can subscribe or unsubscribe to a user. There are also different types of user filtering, by type and name.

Table of Contents
Technologies Used
Installation
Usage
API
Routes
Technologies Used
React
React Router
Axios
MockAPI
Styled-components
Installation
$ git clone https://github.com/Siryi-Oleksandr/tweet-card-test.git
$ cd your-project
$ npm install
$ npm start

Usage
You can freely move between pages. On Tweets page choose any interesting user and subscribe and follow it. Or conversely, you can unsubscribe from anyone. Also you can filter users by name or status of the subscription. You have many variants to quickly find some user using filters by name and status of the users.

API
The app uses the MockAPI service to simulate a backend. The users resource has been created and the user object has the following fields: id, user, tweets, followers, avatar. Pagination, filtering implemented through the backend.

Routes
'/' - Home page
'/tweets' - Tweets page