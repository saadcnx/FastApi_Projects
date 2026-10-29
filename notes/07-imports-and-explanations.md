# 12. Imports & Why Each One

- "First, we'll start with imports. First we have FastAPI: `from fastapi import FastAPI`. I'll turn off AI suggestions, otherwise yes, you'll get annoyed. Alright. So we imported FastAPI."
- "Along with that, we'll also install Pydantic and import `BaseModel` from it, and import `List` from Python's typing. Let me explain what each will be used for."
- "First, we need `BaseModel` from Pydantic. Many AI code editors can trouble you, so I'll turn this off too. And we also import `List` from typing: `from typing import List`. Okay."

# Code
- from fastapi import FastAPI
- from pydantic import BaseModel
- from typing import List

## Explanation
- "Now let's understand one by one why we install these and what the reason is."
- "**FastAPI core** is our framework on which we'll build all the APIs."
- "**`BaseModel`** comes from Pydantic. What does `BaseModel` do? It helps with validation. Whatever Python request comes—a web request—some data will come in it, and you'll also send some data. The data you send should have some structure and syntax. We can define the guidelines for that structure/syntax using Pydantic."
- "Inside `BaseModel`, there is a default base model defined, and we override it so that it can check all those things. That's the basic idea."
