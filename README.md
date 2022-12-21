# Snip Search

Snip search combines Google results and GPT-3 to give concise answers to search queries, with citations.

## Screenshots

| Technical QA                    | Recommendation |
|---------------------------------|----------------|
| ![Search 1](images/screen1.png) | ![Search 2](images/screen2.png)   |

## Example

`What are alternatives to FastAPI?`

```FastAPI and Flask are two popular Python web frameworks used to build APIs and web applications. FastAPI is a full-stack framework that offers everything you need to build an API, while Flask is a micro framework that doesn't provide all the features that FastAPI does. FastAPI focuses on reliability, security, and simplicity, and is designed to build APIs easily and quickly. Flask is less well-documented and is slower than FastAPI, but is useful when you want to prototype an idea quickly or build a simple web application. [1]...```

# Installation

* Clone this repository
* Make sure you have Python 3.9+ installed
* Run `pip install -r requirements.txt` to install the needed packages.
* Enter your OpenAI API key in `settings.py` in the `OPENAI_KEY` variable
* Run `python app.py` to run the application.

# Usage

* Visit `http://127.0.0.1:5000` to see the search interface.
* Enter a search query and click "Search".  Questions work best.
* It can take 10-20 seconds to get results, depending on the query.  You should see the summary and the sources.