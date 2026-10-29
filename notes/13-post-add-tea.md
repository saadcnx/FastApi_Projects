# 19. POST `/teas` — Add a Tea

- "Now let's also do small CRUD operations: how to use POST method to add a Tea, how to edit, and how to delete. After that, we'll see how our documentation is generated."
- "First, we write our decorator. Simply use `@app.post("/teas")` this time because we have to add a new post. No big deal. It depends on how you want to do it."
- "Then simply create a method. Let's call it **`add_tea`**."
- "Now what do we have to do? We don't have to do much. Inside `add_tea`, whatever Tea data is coming—right now we're not doing much validation—just append the Tea data into `teas`. So inside our `teas`, we append `tea`. And that's it."
- "Now obviously `tea` is not available to us yet. So inside this method, we'll expect that whoever is sending us the request will send Tea. Okay? But because we've used Pydantic, I can define its data type: **your type will be `Tea`**. So automatically, all three fields become **mandatory**."
- "See how easy it is? Yes, this remains very easy. And finally, I want to return the Tea that you sent. So inside POST, I return it to you. If I want, I can also add a customized message: 'Tea was added successfully' or whatever you want to do."