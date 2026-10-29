# 13. Creating the App Instance

- "Whenever you build in FastAPI, first we create an app, which we get from FastAPI, something like this. It will look almost like Express-like syntax."
- "Now the first thing we do—usually in separate files or all together—is create **models**."
- "Mostly with Pydantic you'll create **two models**: one for the data coming into your web request, and one for the data you're sending out. For now, we won't go that far, but still let's make a small basic one."

---

# 14. Pydantic Model — Tea

- "So `class Tea(BaseModel):`—as always, and it will inherit from our `BaseModel`. The structure is the same—it always remains the same."
- "Inside this, I'll define the structure of Tea. Tea will always have an **`id`**, which will be an **integer** type."
- "Besides that, Tea will have a **`name`**, which will be a **string** type."
- "And besides that, it will have an **`origin`**—whether it came from Assam or from some foreign country, we'll see—and that will also be a **string** type."
- "So just like we create models—basically the data structure—we'll create the structure like this. These structures can be quite complex. For now, we're keeping it very basic because obviously it's a crash course."