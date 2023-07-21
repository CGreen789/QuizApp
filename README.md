# Week 2 Hackathon/Fetchathon - 🤔 QUIZ APP 🤔

Week 2 was a blur of functions and access data from an API. I had the pleasure of working with Ben and Bianca this week - we clicked quickly and supported each other through the process. 

We chose to create a quiz app using the Quiz question API (https://opentdb.com/api_config.php) and planned that our MVP would allow the user to:
  - Choose a number of questions
  - Choose a category
  - Select the difficulty.

We took some time to get the correct data out from the API and this impacted our ability to move forwards with the MVP. We scaled back the MVP and took out some options for the user...!

Overall a successful day seeing as we'd only just finished week 2.

I'd like to revisit this and take some notes on what I could do to improve/build functionality.





___
## School of Code's instructions

# Fetch Hackathon

Today, we will be using our newfound skills to make apps that request data from a server.

## Step 1 - Getting data and brainstorming (20 - 30 mins)

Here are some APIs that we can use for free. All but the dad jokes one simply need the url. Each API has documentation on how to ask for different data by changing the url. We have included an example fetch for each one to help you get started.

👉 Send a request to each of the APIs below using your browser's address bar to investigate what you get back and check that the APIs are each up and running.

👉 Try and fetch in your JavaScript and console log until you see the same data you saw in the browser.

👉 Visit the documentation for the APIs and investigate further. 

👉 From there, brainstorm what you could make with your knowledge of JavaScript, the DOM and the data you have received.

### Pokemon API

- [Pokemon API](https://pokeapi.co/)

```js
// fetch the first pokemon
fetch("https://pokeapi.co/api/v2/pokemon/1/");
```

### Trivia API

- [Trivia API](https://opentdb.com/api_config.php)

```js
// fetch 10 random questions
fetch("https://opentdb.com/api.php?amount=10");
```

### Dad Jokes API

- [Dad Jokes API](https://icanhazdadjoke.com/api)

```js
// fetch a dad joke
fetch("https://icanhazdadjoke.com/", {
  headers: { accept: "application/json" },
});
```

### Dictionary API

- [Dictionary API](https://dictionaryapi.dev/)

```js
// fetch the definition of the word "hello" in British English (other languages available in the docs)
fetch(`https://api.dictionaryapi.dev/api/v2/entries/en_GB/hello`);
```

## Step 2 - Break down the problem (20 - 30 mins)

Now that you have an understanding of what data you're working with and have come up with an idea of what you could achieve, break down the problem into smaller chunks. Keep breaking the problem down until you can translate your plan into code. You should dream big, break it down, and start small. If your plan turns out to be overly ambitious, then be smart and reign it in. If you've been too conservative, try and push yourself.

## Step 3 - Build (The rest of the day!)

Translate your plan into code, and turn your ideas into reality. Enjoy!
