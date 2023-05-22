# 5. HTTP RESPONSE CODES

**HTTP response codes** are standardized status codes returned by web servers to indicate the result of a client request. They are three-digit codes that provide information about the status of the requested resource or the outcome of the server's attempt to satisfy the client's request.

## Contents

This cheatsheet provides information about:
- class of the response code;
- number;
- meaning/function.

Each HTTP response code is composed of a numeric code and a descriptive phrase, separated by a space. The first digit of the numeric code indicates the response class, while the second and third digits indicate more granular information about the status of the response.

There are five classes of HTTP response codes, each with its own set of numeric codes and meaning:
- Informational response (100-199): These codes indicate that the server has received the request and is continuing to process it.
- Successful response (200-299): These codes indicate that the server successfully processed the request and returned the requested resource.
- Redirection response (300-399): These codes indicate that further action needs to be taken by the client to complete the request.
- Client error response (400-499): These codes indicate that the server was unable to process the request due to an error or invalid request from the client.
- Server error response (500-599): These codes indicate that the server encountered an error while processing the request.

![HTTP Response Codes](https://user-images.githubusercontent.com/119814239/224755907-1351e369-a002-45f1-86ea-2c726f723bfb.png)

### Sources

`Hypertext Transfer Protocol (HTTP/1.1): Status Code Definitions. (2014). IETF. https://datatracker.ietf.org/doc/html/rfc7231#section-6`

`HTTP response status codes. (2022, January 13). Mozilla. https://developer.mozilla.org/en-US/docs/Web/HTTP/Status`

## License

This repository is licensed under the MIT License
