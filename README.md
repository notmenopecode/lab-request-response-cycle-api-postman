# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> http://restcountries.com

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is... The REST countries API provides information about countries such as the country capital, population, region, currency, languages spoken, flag images, and more.

- What is the URL of the documentation?

> http://

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://restcountries.com/v3.1/name/peru

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
[
    {
        "name": {
            "common": "Peru",
            "official": "Republic of Peru",
            "nativeName": {
                "aym": {
                    "official": "Piruw Suyu",
                    "common": "Piruw"
                },
                "que": {
                    "official": "Piruw Ripuwlika",
                    "common": "Piruw"
                },
                "spa": {
                    "official": "República del Perú",
                    "common": "Perú"
                }
            }
        },


``` 

- What status code did you get back from your request? Why did you receive this status code?

> 00 I got a statuse code of '200 0k' which indicates that the request was successful

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: 1336

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes... 
country name,
 pronunciations of country name,
  geographical information,
   region,
    subregion,
     area,
      demographic information,
       flag and country code,
        languages, time zone,
         currency, etc...

  The response given was extremely thorough and of course informational. Providing every little detail about whatever country you may choose to research. In this case, I chose Peru.    

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ... has some sore of trivia game asset to it. Let's say we have a quiz game app and one of the categories is 'Countries', we can use this API to filter through the different countries and provide information that fuel the questions.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is the communication between a client(a website/app) and a server. The communication itself occurs through the HTTP.

- In your own words, describe what an API is.

> An API is ... a software middleman that allows two applications to talk to each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... makes the process of working with APIs simple by providing a user-friendly interface.
