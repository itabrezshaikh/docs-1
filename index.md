# Getting Started with Pepipost API

You can try Pepipost API online with Pepipost Live API console at <a href="https://docs.pepipost.com/console/" target="_blank"> https://docs.pepipost.com/console/ </a>.

## Available APIs types

Pepipost APIs are not completely REST complaint. We have 2 types of API to send an email:
    
* REST
* JSON


Our REST APIs are those APIs, which accept each parameters as a separate HTTP variable. 

**Example:**

```
https://api.pepipost.com/api/example.rest?foo=bar&foz=baz
```

Our JSON APIs are those APIs, which accept all parameters formatted as a JSON string provided as a value of single paramater (namely, data).

**Example:**

```
https://api.pepipost.com/api/example.rest?data={"foo":"bar","foz":"baz"}
```

### The base URL for all of our APIs is always:

```
https://api.pepipost.com/api/
```
## Available APIs
  
* REST/Email send
* JSON/Email send

## Requirements

In order to use our API:

* You need sign up for a Pepipost account, login and get the API key.
* Add & approve your sender domain








