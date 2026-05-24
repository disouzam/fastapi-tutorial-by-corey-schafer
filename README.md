# About this repository

Repository to follow along Python FastAPI Tutorial by Corey Schafer on YouTube - a 19-part playlist at https://youtube.com/playlist?list=PL-osiE80TeTsak-c-QsVeg0YYG_0TeyXI

## Video 1 - Python FastAPI Tutorial (Part 1): Getting Started - Web App + REST API

[Python FastAPI Tutorial (Part 1): Getting Started - Web App + REST API](https://youtu.be/7AMjmCTumuo)

> In this series of videos, we'll be learning how to build a full-featured web application from the ground up using the FastAPI framework in Python. We'll build both a JSON API for programmatic access and HTML pages for users to browse in the browser. Throughout the series, we'll set up a database with SQLAlchemy, create Pydantic models for data validation, and implement complete CRUD operations. We'll add user registration and login with secure password hashing and JWT tokens, handle file uploads for profile pictures, use background tasks for sending emails, and organize our code properly with routers.

> In this first video, we'll keep things simple. We'll install FastAPI, create a basic application, build a couple of routes that return JSON, run the app from the command line, and explore FastAPI's automatic documentation. Then we'll add some dummy data, create an API endpoint, and preview returning HTML responses. Let's get started...

> The code from this video can be found here:
> https://github.com/CoreyMSchafer/FastAPI-01-Getting-Started
>
> Extracted from YouTube description by @coreyMschafer

## Video 2 - Python FastAPI Tutorial (Part 2): HTML Frontend for Your API - Jinja2 Templates

[Python FastAPI Tutorial (Part 2): HTML Frontend for Your API - Jinja2 Templates](https://youtu.be/G4NIB9Rx9Qs)

> In this Python FastAPI tutorial, we'll be learning how to use Jinja2 templates to create an HTML frontend for our API. Templates allow us to serve proper HTML pages to users while keeping our JSON endpoints intact for the backend API. We'll cover setting up Jinja2Templates, passing data to templates, using Jinja2 syntax for loops and conditionals, implementing template inheritance with a layout file, adding Bootstrap for styling, and configuring static files for CSS and images. By the end of this video, we'll have a nicely styled blog homepage that displays our posts. Let's get started...

> The code from this video can be found here: https://github.com/CoreyMSchafer/FastAPI-02-Templates
>
> Extracted from YouTube description by @coreyMschafer

## Video 3 - Python FastAPI Tutorial (Part 3): Path Parameters - Validation and Error Handling

[Python FastAPI Tutorial (Part 3): Path Parameters - Validation and Error Handling](https://youtu.be/WRjXIA5pMtk)

> In this Python FastAPI tutorial, we'll be learning how to use path parameters in FastAPI to create dynamic routes that can fetch specific resources from our data. We'll build both an API endpoint and a template page for viewing individual posts, add type validation with proper error handling using HTTPException, and create custom exception handlers that return JSON for API routes and styled HTML pages for browser routes. By the end, you'll have a solid understanding of how to work with path parameters, validate input automatically, and handle errors appropriately for different types of clients. Let's get started...

> The code from this video can be found here:
> https://github.com/CoreyMSchafer/FastAPI-03-Path-Parameters
>
> Extracted from YouTube description by @coreyMschafer

## Video 4: Python FastAPI Tutorial (Part 4): Pydantic Schemas - Request and Response Validation

[Python FastAPI Tutorial (Part 4): Pydantic Schemas - Request and Response Validation](https://youtu.be/9GHxnttXxrA)

> In this Python FastAPI tutorial, we'll be learning how to use Pydantic schemas to validate API requests and responses in FastAPI. We'll create a schemas file with request and response models, add field validations for things like minimum and maximum length, update our GET endpoints with response models, and create a POST endpoint to add new posts. Pydantic schemas define your API contract - what data goes in and what comes out - and FastAPI uses them for validation, serialization, and automatic documentation. Let's get started...

> The code from this video can be found here: https://github.com/CoreyMSchafer/FastAPI-04-Pydantic-Schemas
>
> Extracted from YouTube description by @coreyMschafer

# Useful commands:

```bash
# With auto-reload and more support to debug
uv run fastapi dev main.py
```
