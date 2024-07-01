# Status

A simple Node.js module that provides HTTP status, inspired by Django Rest Framework's status codes.

## Installation

You can install the package via npm:

```bash
npm install rest-http-status
```

## Usage

First, require the package in your project:

```javascript
const status = require('rest-http-status');
// You can then use the status codes as follows:

// Informational - 1xx
console.log(status.HTTP_100_CONTINUE); // 100

// Successful - 2xx
console.log(status.HTTP_200_OK); // 200

// Redirection - 3xx
console.log(status.HTTP_300_MULTIPLE_CHOICES); // 300

// Client Error - 4xx
console.log(status.HTTP_400_BAD_REQUEST); // 400

// Server Error - 5xx
console.log(status.HTTP_500_INTERNAL_SERVER_ERROR); // 500
```

## Informational - 1xx

| Constant                                  | Code |
| ----------------------------------------- | ---- |
| HTTP_100_CONTINUE                         | 100  |
| HTTP_101_SWITCHING_PROTOCOLS              | 101  |
| HTTP_102_PROCESSING                       | 102  |
| HTTP_103_EARLY_HINTS                      | 103  |

## Successful - 2x

| Constant                                  | Code |
| ----------------------------------------- | ---- |
| HTTP_200_OK                               | 200  |
| HTTP_201_CREATED                          | 201  |
| HTTP_202_ACCEPTED                         | 202  |
| HTTP_203_NON_AUTHORITATIVE_INFORMATION    | 203  |
| HTTP_204_NO_CONTENT                       | 204  |
| HTTP_205_RESET_CONTENT                    | 205  |
| HTTP_206_PARTIAL_CONTENT                  | 206  |
| HTTP_207_MULTI_STATUS                     | 207  |
| HTTP_208_ALREADY_REPORTED                 | 208  |
| HTTP_226_IM_USED                          | 226  |

## Redirection - 3xx

| Constant                                  | Code |
| ----------------------------------------- | ---- |
| HTTP_300_MULTIPLE_CHOICES                 | 300  |
| HTTP_301_MOVED_PERMANENTLY                | 301  |
| HTTP_302_FOUND                            | 302  |
| HTTP_303_SEE_OTHER                        | 303  |
| HTTP_304_NOT_MODIFIED                     | 304  |
| HTTP_305_USE_PROXY                        | 305  |
| HTTP_306_RESERVED                         | 306  |
| HTTP_307_TEMPORARY_REDIRECT               | 307  |
| HTTP_308_PERMANENT_REDIRECT               | 308  |

## Client Error - 4xx

| Constant                                  | Code |
| ----------------------------------------- | ---- |
| HTTP_400_BAD_REQUEST                      | 400  |
| HTTP_401_UNAUTHORIZED                     | 401  |
| HTTP_402_PAYMENT_REQUIRED                 | 402  |
| HTTP_403_FORBIDDEN                        | 403  |
| HTTP_404_NOT_FOUND                        | 404  |
| HTTP_405_METHOD_NOT_ALLOWED               | 405  |
| HTTP_406_NOT_ACCEPTABLE                   | 406  |
| HTTP_407_PROXY_AUTHENTICATION_REQUIRED    | 407  |
| HTTP_408_REQUEST_TIMEOUT                  | 408  |
| HTTP_409_CONFLICT                         | 409  |
| HTTP_410_GONE                             | 410  |
| HTTP_411_LENGTH_REQUIRED                  | 411  |
| HTTP_412_PRECONDITION_FAILED              | 412  |
| HTTP_413_REQUEST_ENTITY_TOO_LARGE         | 413  |
| HTTP_414_REQUEST_URI_TOO_LONG             | 414  |
| HTTP_415_UNSUPPORTED_MEDIA_TYPE           | 415  |
| HTTP_416_REQUESTED_RANGE_NOT_SATISFIABLE  | 416  |
| HTTP_417_EXPECTATION_FAILED               | 417  |
| HTTP_421_MISDIRECTED_REQUEST              | 421  |
| HTTP_422_UNPROCESSABLE_ENTITY             | 422  |
| HTTP_423_LOCKED                           | 423  |
| HTTP_424_FAILED_DEPENDENCY                | 424  |
| HTTP_425_TOO_EARLY                        | 425  |
| HTTP_426_UPGRADE_REQUIRED                 | 426  |
| HTTP_428_PRECONDITION_REQUIRED            | 428  |
| HTTP_429_TOO_MANY_REQUESTS                | 429  |
| HTTP_431_REQUEST_HEADER_FIELDS_TOO_LARGE  | 431  |
| HTTP_451_UNAVAILABLE_FOR_LEGAL_REASONS    | 451  |

## Server Error - 5xx

| Constant                                  | Code |
| ----------------------------------------- | ---- |
| HTTP_500_INTERNAL_SERVER_ERROR            | 500  |
| HTTP_501_NOT_IMPLEMENTED                  | 501  |
| HTTP_502_BAD_GATEWAY                      | 502  |
| HTTP_503_SERVICE_UNAVAILABLE              | 503  |
| HTTP_504_GATEWAY_TIMEOUT                  | 504  |
| HTTP_505_HTTP_VERSION_NOT_SUPPORTED       | 505  |
| HTTP_506_VARIANT_ALSO_NEGOTIATES          | 506  |
| HTTP_507_INSUFFICIENT_STORAGE             | 507  |
| HTTP_508_LOOP_DETECTED                    | 508  |
| HTTP_509_BANDWIDTH_LIMIT_EXCEEDED         | 509  |
| HTTP_510_NOT_EXTENDED                     | 510  |
| HTTP_511_NETWORK_AUTHENTICATION_REQUIRED  | 511  |
