# qKast
qKast API documentation and examples

qKast API provides programmatic access to qKast functionality and content.
Version 1 of the API is limited to the essentials of the website's functionality: allowing the creation of new widgets, accessing UI internals, and getting information.

The information API is [REST API](http://en.wikipedia.org/wiki/Representational_State_Transfer "RESTful")
The return format for all endpoints is [JSON](http://json.org/ "JSON").

See [status.qkast.com](http://status.qkast.com) for API status updates, outages, and scheduled maintenance.

***

## Checklist
* [Grab the bookmarklet](https://qkast.com)
* Familiarize yourself with API functionality
* Hack away

***

## Examples

- **[JavaScript](http://500px.github.com/500px-js-sdk)**
- **[iOS](https://github.com/500px/api-documentation/blob/master/examples/iOS/API%20Tutorials.md)**
- **[Ruby](https://github.com/500px/api-documentation/blob/master/examples/Ruby/)**
- **[PHP](https://github.com/500px/api-documentation/blob/master/examples/PHP/PHP.md)**

## Changes

* 12-9-16 qKast API documentation launched.

## Endpoints

#### Widget

- **[<code>GET</code> widget](https://github.com/500px/api-documentation/blob/master/endpoints/widget/GET_widgets.md)**
- **[<code>GET</code> widget/:id](https://github.com/500px/api-documentation/blob/master/endpoints/widget/GET_widget_id.md)**

## FAQ
### What do I need to know before I start using the API?
Got rust on your skills? No worries. Here are the docs you might need to get started:

- HTTPS protocol
- [REST software pattern][]
- Data serialization with [JSON][] (or see a [quick tutorial][])

### How do I connect to the 500px.com API?
Generally, reading any data is done through a request with GET method. If you want our server to create, update or delete a given resource, POST or PUT methods are required on supported end points.

### What return formats do you support?
qKast API currently returns data in [JSON](http://json.org/ "JSON") format.

### What kind of authentication is required?
There is no authentication required right now.

### Is there a request rate limit?
There is a rate limit of 10,000 API requests per month per account. We will contact you and if required disable your application if we find that your application is exceeding this limit or interfering with our system's stability.This revised rate limit will come into effect January 1, 2017.

[REST software pattern]: http://en.wikipedia.org/wiki/Representational_State_Transfer
[JSON]: http://json.org
[quick tutorial]: http://www.webmonkey.com/2010/02/get_started_with_json/
[Register your application]: https://qkast.com/share?channel=69
[API Terms of Use]: https://github.com/qkast/api-documentation/blob/master/basics/terms_of_use.md
