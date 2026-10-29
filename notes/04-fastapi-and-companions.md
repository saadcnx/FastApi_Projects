# 7. What is FastAPI + Its Companions

- "So this is FastAPI, and simply put, it is a **modern, high-performance web framework for building APIs**."
- "It has many features—it's not just what's written here. Actually, the roadmap/standard is much bigger than this. I don't think maybe the home page has been updated as much as it should have been."
- "But FastAPI doesn't work alone. FastAPI needs some companions, and it has its siblings."

## 7.1 Uvicorn (biggest sibling)
- "Its biggest sibling is **Uvicorn**. Uvicorn is nothing fancy—it's a basic web server, a pure web server implementation. You can run FastAPI directly, but most coders will run it through Uvicorn."
- "Now FastAPI also has its own built-in web server; that too is actually built on top of Uvicorn. But now you can do it directly too. That's the whole thing."

## 7.2 Pydantic
- "And whatever Python web application you develop, almost all companies and corporates use one standard: **Pydantic**."
- "Pydantic also has its own AI—we'll talk about that sometime too. Tell me in the comments if we should talk about it sometime. So yes, Pydantic AI is also a thing in itself."
- "What does Pydantic do? Pydantic is a **data validation library**."
- "As we know, Python doesn't define data types that well. Pydantic fills that gap. Just like **TypeScript** fills that gap in JavaScript—so you get all the types you need—Pydantic does the same job. But Pydantic is even more powerful."
- "We'll look at Pydantic a little—not too much, only as much as we need for this crash course. Sometime we'll do a Pydantic series and all that."

## 7.3 typing module
- "And one small module we'll use is the **typing** module. It's very simple. You get `List`, type hints, etc. It's nothing very special—it's a **core Python module**."
- "So we have **FastAPI, Uvicorn, and Pydantic**. Using these, we'll try to build a basic web application."