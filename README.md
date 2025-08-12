CrptApi Java Client

This project contains a thread-safe Java class CrptApi for interacting with the Honest Sign (Честный Знак) API. It implements a request rate limiter to ensure the number of API calls does not exceed a specified limit within a given time interval.
Features

    Thread-safe implementation supporting concurrent use.

    Rate limiting based on requests per time unit (seconds, minutes, etc.).

    Method to create a document for "putting into circulation" goods produced in Russia.

    Uses Java 11 features and standard libraries for HTTP requests and JSON serialization.

    Designed with extensibility in mind for future API methods.

Notes

    The solution is provided as a single Java file (CrptApi.java) with all auxiliary classes implemented internally.

    This is a test task implementation based on provided API documentation.

    Some parts are simplified due to time constraints and task scope, focusing on correctness and basic functionality.
