
Okay, so, typing whatever is coming to my mind quickly about FastAPI:
---------------------------------------------------------------------

Creating APIs, or **application programming interfaces**, is an important part of making software accessible to a broad range of users. A quick run through the main concepts of **FastAPI** and how to use it to quickly create web APIs that implement best practices by default.

By the end of it, i will have production-ready web APIs, and better understanding to go deeper and learn more for your specific use cases.

**This quick FastAPI practice repo will ensure how to**:

*   Use **path parameters** to get a unique URL path per item
*   Receive JSON data in your requests using **pydantic**
*   Use API best practices, including **validation**, **serialization**, and **documentation**
*   Continue learning about FastAPI for **your use cases**

 It contains a careful selection of fragments from the official documentation, avoiding getting lost in technical details while helping you get up to speed as fast as possible.

To get the most out of it, it would be helpful for you to know the basics of "What HTTP is and how it works", "What JSON is", and "Python type hints". You will also benefit from using a virtual environment, as is the case for any Python project.


So, What Is FastAPI?
-----------------------------------------------------

FastAPI is a modern, high-performance web framework for building APIs with Python based on standard type hints. It has the following key features:

*   **Fast to run**: It offers very high performance, on par with **NodeJS** and **Go**, thanks to [Starlette] and [pydantic]
*   **Fast to code**: It allows for significant increases in development speed.
*   **Reduced number of bugs**: It reduces the possibility for human-induced errors.
*   **Intuitive**: It offers great editor support, with completion everywhere and less time debugging.
*   **Straightforward**: It’s designed to be uncomplicated to use and learn, so you can spend less time reading documentation.
*   **Short**: It minimizes code duplication.
*   **Robust**: It provides production-ready code with automatic interactive documentation.
*   **Standards-based**: It’s based on the open standards for APIs, [OpenAPI](https://github.com/OAI/OpenAPI-Specification) and [JSON Schema](https://json-schema.org/).

The framework is designed to optimize your developer experience so that we all can write simple code to build production-ready APIs with best practices by default.



Install FastAPI
----------------------------------------------------

As with any other Python project, it would be best to start by creating a virtual environment. If you are not familiar with how to do that, then you can check out the [Primer on Virtual Environments](https://realpython.com/python-virtual-environments-a-primer/).

The first step is to install FastAPI and [Uvicorn](https://www.uvicorn.org/#introduction) using [`pip`](https://realpython.com/what-is-pip/):

...

and..so..on
