# 8. Editor & Folder Setup

- "Let's go. We've reached our editor. Inside this editor, I've opened a basic folder. Now we want to build a Python application here."
- "Actually, there should be a separate video on FastAPI setup too, but that's for later—right now it's a crash course."

---

# 9. Virtual Environment Creation

- "First, we'll create a virtual environment. I'll write `python3`. You write `python`, because I'm on a Mac. You may be on Windows or Linux. So I'll write `python3 -m venv venv`."
- "`venv` is a package. With this, I want to create a virtual environment. I can name it `venv` or `api`—whatever you want. Many people name it `.venv` because they want to keep the folder hidden. No problem—name it however you like."
- "As soon as I press Enter, a whole virtual environment folder is created here."
- "**Virtual environment is important** because when this package has to be taken somewhere else, the environment here and the environment in production should remain the same."

## Activation
- "To activate it, I can simply `source venv/bin/activate`. If you're on Windows, directly use `venv\Scripts\activate`."
- "You already know that—I explained it in the Django series. Otherwise, a small Google search will do it."
- "Now my virtual environment is active. Now I don't need to write `python3` etc. I can directly write `python`. Similarly, I don't need to write `pip3`; I can install directly with `pip`."