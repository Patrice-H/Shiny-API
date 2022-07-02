# Shiny - Agency - API

This repo contains the API code you will need to run the Shiny-Agency app.
It goes hand in hand with [the repository of the frontend part](https://github.com/Patrice-H/Shiny_Agency.git).


## Install the API locally

To install the API locally on your machine, you must :
1. Clone it on your computer `git clone https://github.com/OpenClassrooms-Student-Center/7150606-API-React-intermediaire.git`
2. Install `node_modules` with `npm install`
3. Run the API with `npm start`


## Consume the API

Once launched, this API makes several routes available to you :

- Route to recover the profiles of freelancers :
`GET /freelances`

- Route to get the details of a freelance profile :
`GET /profile/?id={id}`

- Route to get the questionnaire :
`GET /survey/`

- Route to get the result of the questionnaire :
`GET /results/?a1={answer1}&a2={answer2}&a3={answer3}...`