# Prestige
Test website reputation, analyze author for trustworthiness, understand important concepts, and be provided with a succinct summary.

## Link
https://prestige-web-app.herokuapp.com/

## Audience
Readers who want to be more informed about the legitimacy of an article or who may be unfamiliar with the subject matter. Also useful for writers checking for article bias.

## Experience
The user enters the webpage, and sees the option to enter a website url that links to an article. They then press a button to analyze their inputs and are returned with understandable and visually appealing results. Additional features to have the article read out loud and also the option to have it translated will be implemented later.

# Technical
## Views
- Index/Home
- Website Reputation
- Writer's Legitimacy
- Sentiment Report
- Article Summary

## Routes (Slightly inaccurate due to the addition of React)
- Index/Home/NewAnalysis
  - GET <span></span>www.prestige.com/
- WebsiteReputation/WriterLegitimacy/SentimentReport/ArticleSummary
  - GET <span></span>www.prestige.com/result
  - POST <span></span>www.prestige.com/results

## Features
- Input for links
- Results page with analysis and summary
- Option to translate the article and its summary
- Option to translate the site

## Languages
#### Front-End
* HTML
* CSS
* JavaScript
* React
* Chart.js
* SweetAlert2
#### Back-End
* Node.js
* Express.js
* IBM Watson Natural Language Classifier
* IBM Watson Personality Insight
* Aylien Extract
* Aylien Summarize
* Aylien Sentiment
* Web of Trust

## Planning
- Week One
  - Monday July 23, 2018
    - Design document
    - Node.js, Express.js and API setup
  - Tuesday July 24, 2018
    - Experiment with APIs and learn their calls
  - Wednesday July 25, 2018
    - Create front end skeleton
    - Receive data from the APIs
    - Create the results data model
  - Thursday July 26, 2018
    - Have working functionality for the webpage
  - Friday July 27, 2018
    - Complete MVP
    - Learn React
    - Connect the front end with the back end (React & Express.js)
  - Saturday July 28, 2018
    - Send url to the back end and receive JSON data
    - Complete the components and their interaction for React
  - Sunday
    - Create charts to visually represent analysis and results
- Week Two
  - Monday July 30, 2018
    - Complete charts
    - Refine design and complete the front-end
  - Tuesday July 31, 2018
    - CSS and JavaScript animations
  - Wednesday August 1, 2018
    - Refining front end design
  - Thursday August 2, 2018
    - Upload the page to Heroku
    - Completed Version 1.0
