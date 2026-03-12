# Async Weather Tracker 🌤️

This is my lab submission for Web Dev II (Advanced JS & React)[cite: 2]. [cite_start]It's a weather tracking app built completely with plain HTML, CSS, and Vanilla JavaScript[cite: 24, 28]. [cite_start]No external UI frameworks like Bootstrap or Tailwind were used, keeping in line with the assignment restrictions[cite: 27].

## What it does
The main focus of this project is to handle asynchronous programming and analyze how JavaScript behaves at runtime[cite: 7]. 

Features included:
* **Weather Search:** Uses the OpenWeatherMap API to fetch current weather data using `async/await` and the Fetch API.
* **Error Handling:** Gracefully handles invalid city names, broken API responses, or network issues using `try...catch` blocks.
* **Search History:** Saves previous searches using Local Storage so they persist on page reload[cite: 47, 48]. [cite_start]Clicking a past search instantly re-fetches that city's weather.
* **Event Loop Console:** A custom on-screen console that tracks the execution order of synchronous code, microtasks (`Promise.then`), and macrotasks (`setTimeout`) to visualize the call stack and event loop.
