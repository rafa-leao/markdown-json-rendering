# markdown-json-rendering

- Example of JSON 1:

*The following JSON works perfectly on mobile as in the browser* 

```json

{
  "key": "value",
  "key1": {
    "key2": "value2"
  }
}

```

- Example of JSON 2:

*This case in specific I made a tiny documentation of my web api and I came up with this format*

*In this case it breaks. It kinda makes sense because of indentation*

- Title
    - **Description**
        - ` POST ` ` /user/ `
        - Request payload
        ```json
            {
                "email": "example@example.com",
                "password": 123123
            }
        ```
