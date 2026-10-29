# 17. GET `/` — Home Route

- "So first we do `@app.get("/")`. Inside, you define the verb—GET, POST, PUT, whatever. Right now we have GET, and inside it we define the `/` route. This is the decorator."
- "Just after this decorator comes the method definition. We can name this method whatever we want. Let's name it **`read_root`**—meaning read the root message."
- "Now I simply return an object from here. We call this a simple message: `{"message": "Welcome to Chai Code"}`. Which Tea House? We'll say Chai Code, right? Welcome to Chai Code. That's it. Your home route is ready."