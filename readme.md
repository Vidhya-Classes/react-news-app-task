
# Assignment 1: News Blog Website using React

## Objective:

The objective of this application is to understand the fundamentals of React and build a news blog website that fetches data from the [News API](https://newsapi.org/).

## Estimated Effort:

The estimated effort to complete this assignment is 3-4 hours.

## Things to Do:

-   Create a Vite project
-   Complete the below assignment
-   Push the code to Git
-   Submit the solution via GitHub

## Expected Outcome:

By the end of the assignment, you should be able to understand:

1.  Modules
2.  Components
3.  React with Bootstrap or any design library
4.  Data Binding
5.  Dependency Injection
6.  Services

## The News API to be Used as Data Source

To get the news data, you will be using the [News API](https://newsapi.org/). You can use the following endpoints to fetch news data:

-   To get category wise news, use the following endpoint: `https://newsapi.org/v2/top-headlines?category=<<news_category>>&apikey=<<api_key>>&page=1`
-   To get trending news, use the following endpoint: `https://newsapi.org/v2/top-headlines?country=in&apikey=<<api_key>>&page=1`
-   To search for any news based on search text, use the following endpoint: `https://newsapi.org/v2/everything?q=<<search_text>>&apiKey=<<api_key>>&language=en&page=1`

To register for an API key, follow these steps:

1.  Signup to [NEWSAPI](https://newsapi.org/register).
2.  After registration, an API key will be generated for you.

## Assignment:

This case study is about showing current and old news and giving you an option to read any news later.

1.  News Manager should use Bootstrap or any Design for its UI.
2.  It should be able to get the news from the News API.
3.  It should be able to load the heading and image of all current news in the form of cards.
4.  Every card should have a "read later" button.
5.  Save the loaded news in local storage and serve data from local storage as a cache for the next 10 minutes.

## Instructions:

1.  To run the application, use `npm run dev`.
2.  The application should contain 4 components:
    -   Card
    -   Dashboard
    -   Footer
    -   Header
3.  All the test cases should be written in the `test` folder inside `src` test folder.
4.  Install all the dependencies using `npm install`.
5.  To test your application, please use the command `npm run test`.
6.  To run the application, use the command `npm start`.
7.  Each and every component should have at least 5 unit test cases each.
8.  Add a `components` folder in `src` to keep your components.
9.  Create an organized folder structure.

### Card Component:

-   Used to display the news card, which contains {urlToImage, title, author}.

### Dashboard Component:

-   This component is responsible for getting the information from the News API and passing it to the Card component as a prop.
-   Header and Footer components are used to define the header and footer of the application.

Note: Please recheck the name and case of the component and make sure to follow the proper folder structure.

## Conclusion:

In this assignment, you have learned how to use React to build a news blog website and fetch data from the News API. You have also learned about components, data binding, and services.
