Watch Now This tutorial has a related video course created by the Real Python team. Watch it together with the written tutorial to deepen your understanding: [**Python REST APIs With FastAPI**](/courses/python-rest-apis-with-fastapi/)

Creating APIs, or **application programming interfaces**, is an important part of making your software accessible to a broad range of users. In this tutorial, you will learn the main concepts of **FastAPI** and how to use it to quickly create web APIs that implement best practices by default.

By the end of it, you will be able to start creating production-ready web APIs, and you will have the understanding needed to go deeper and learn more for your specific use cases.

**In this tutorial, you’ll learn how to**:

*   Use **path parameters** to get a unique URL path per item
*   Receive JSON data in your requests using **pydantic**
*   Use API best practices, including **validation**, **serialization**, and **documentation**
*   Continue learning about FastAPI for **your use cases**

This tutorial is written by the [author of FastAPI](https://realpython.com/team/sramirez/). It contains a careful selection of fragments from the official documentation, avoiding getting lost in technical details while helping you get up to speed as fast as possible.

To get the most out of this tutorial, it would be helpful for you to know the basics of [what HTTP is and how it works](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview), [what JSON is](https://realpython.com/python-json/), and [Python type hints](https://fastapi.tiangolo.com/python-types/). You will also benefit from using a [virtual environment](https://realpython.com/python-virtual-environments-a-primer/), as is the case for any Python project.

**Free Bonus:** [5 Thoughts On Python Mastery](https://realpython.com/bonus/python-mastery-course/), a free course for Python developers that shows you the roadmap and the mindset you’ll need to take your Python skills to the next level.

What Is FastAPI?[](#what-is-fastapi "Permanent link")
-----------------------------------------------------

FastAPI is a modern, high-performance web framework for building APIs with Python based on standard type hints. It has the following key features:

*   **Fast to run**: It offers very high performance, on par with **NodeJS** and **Go**, thanks to [Starlette](https://www.starlette.io/) and [pydantic](https://pydantic-docs.helpmanual.io/).
*   **Fast to code**: It allows for significant increases in development speed.
*   **Reduced number of bugs**: It reduces the possibility for human-induced errors.
*   **Intuitive**: It offers great editor support, with completion everywhere and less time debugging.
*   **Straightforward**: It’s designed to be uncomplicated to use and learn, so you can spend less time reading documentation.
*   **Short**: It minimizes code duplication.
*   **Robust**: It provides production-ready code with automatic interactive documentation.
*   **Standards-based**: It’s based on the open standards for APIs, [OpenAPI](https://github.com/OAI/OpenAPI-Specification) and [JSON Schema](https://json-schema.org/).

The framework is designed to optimize your developer experience so that you can write simple code to build production-ready APIs with best practices by default.

[Remove ads](/account/join/)

Install FastAPI[](#install-fastapi "Permanent link")
----------------------------------------------------

As with any other Python project, it would be best to start by creating a virtual environment. If you are not familiar with how to do that, then you can check out the [Primer on Virtual Environments](https://realpython.com/python-virtual-environments-a-primer/).

The first step is to install FastAPI and [Uvicorn](https://www.uvicorn.org/#introduction) using [`pip`](https://realpython.com/what-is-pip/):

Shell
