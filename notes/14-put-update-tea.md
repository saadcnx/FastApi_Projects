# 20. PUT `/teas/{tea_id}` — Update a Tea

- "Let's make one more. `@app.put(...)`. We'll use the PUT method here. Its route will be `/teas/{tea_id}`."
- "After `/teas`, I also need a Tea ID. How do we add `tea_id`? You simply use **curly braces** and give it a name: `tea_id`. Now whatever name you give here, pay attention, because you'll use it again. So the decorator is done."
- "After this, define `def update_tea(...)`."
- "Inside `update_tea`, what will happen? The `tea_id` you wrote above inside curly braces—exactly that you'll expect here in this method. Its data type I expect is an **integer**."
- "Along with that, you'll give me an **`updated_tea`**, because we're updating, so the updated value should also be there. You'll pass me `updated_tea`, and this whole data type will be `Tea`."
- "The ID value tells me which Tea to update, and the updated value tells me what it should become. That's it."
- "After that, what to do? Loop over all the values. Whichever value matches, change it. That's it. So to use it, it's very simple. We'll simply run a loop: `for index, t in enumerate(teas):`. We enumerate over `teas`—our array."
- "Then we match whether the Tea's ID matches our `tea_id`. We do `if t.id == tea_id:`. If it matches, update it. So at that index, we'll directly add `updated_tea` and then return `updated_tea`."
- "But if that doesn't happen, what will we do? We'll return an error. If I come out of the whole loop and didn't find the value anywhere, then simply return an error like `{"error": "Tea not found"}` or whatever message you want to write."
- "See, this way you can **accept dynamic parameters directly inside the function**."