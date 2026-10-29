# 21. DELETE `/teas/{tea_id}` — Delete a Tea

- "Now similarly, let's make DELETE too. When we've made this much, one more should be made, and then our whole CRUD operation will actually be complete."
- "We'll use `@app.delete("/teas/{tea_id}")`. To delete, we also need to send the ID. So you'll send `tea_id`."
- "As soon as you send it, I'll create a method here: `def delete_tea(tea_id: int):`. Now you know its type will be integer. While deleting, I don't need any extra Tea—just pass me the ID, and I'll simply delete it. That's the whole story."
- "Same thing—repeat the same work. We take `index` and `t`, enumerate over `teas`. Now wherever `t.id` matches our `tea_id`, we'll delete it."
- "After deleting, you can return the deleted value if you want; if not, don't. But overall, the work is that we can use the `teas.pop(index)` method, and we need to return that index."
- "Now I know that this `pop` method actually removes the index—it says 'remove and return the item.' So if you want, hold what it returns in a variable. Very simple. Let's call it **`deleted`**, and we hold it in a variable. If you want, return `deleted`."
- "And if, say, we go through the whole loop and still don't find anything to delete, then what do we do? Same thing—return an error: `{"error": "Tea not found"}`."
- "So we performed a very basic operation here. There may be some typos; we'll check errors and all."