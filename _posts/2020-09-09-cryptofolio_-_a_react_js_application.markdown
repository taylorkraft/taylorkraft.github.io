---
layout: post
title:      "CRYPTOFOLIO - A React.js Application"
date:       2020-09-10 02:40:51 +0000
permalink:  cryptofolio_-_a_react_js_application
---


Cryptofolio is an application designed to log your cryptocurrency trades. It was built using a Ruby on rails backend API and a React.js frontend. 

The background relationship is set up in a way where Portfolios have many Trades, and Trades belong to a Portfolio. This API makes use of namespacing, RESTful routing, and custom methods to do things like update your portfolio balance.

On the frontend, we have a redux store setup that allows our frontend data to be stored. The App component renders the PortfoliosContainer, which holds most of the app functionality. We have one reducer - a portfolioReducer that is responsible for updating the parts of our store that have to do with a portfolio. We can only access our trades through a portfolio, so it is also responsible for updating the parts of our store that have to do with trades.

On the UI, we can navigate from our home page to "My Portfolios"

Here, we can create a new portfolio and view our existing portfolios. We can select an existing portfolio to view the balance, and create trades that will reflect in our portfolio log, and update our portfolio balance. From here, we can navigate back to our portfolios, or back to the home page.

Overall, this was a challenge but I am excited with the result and I'm looking forward to furthering my React.js skills.
