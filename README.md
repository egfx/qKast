# qKast
qKast API documentation and examples

qKast API provides programmatic access to qKast functionality and content.
Version 1 of the API is limited to the essentials of the website's functionality: allowing for the creation of new widgets, accessing UI internals, and getting information.

The information API is [REST](http://en.wikipedia.org/wiki/Representational_State_Transfer "RESTful")
The return format for all endpoints is [JSON](http://json.org/ "JSON").

See [status.qkast.com](http://status.qkast.com) for API status updates, outages, and scheduled maintenance.

***

## Checklist
* [Grab the bookmarklet](https://qkast.com)
* Familiarize yourself with the API functionality
* Hack away

***

## Examples

- **[AngularJS](http://)**
- **[React](http://)**
- **[jQuery](http://)**
- **[Vue](http://)**

## Changes

* 12-9-16 qKast API documentation launched.

## Endpoints

#### Widget

- **[<code>GET</code> widget](https://github.com/qkast/api-documentation/blob/master/endpoints/widget/GET_widgets.md)**
- **[<code>GET</code> widget/:id](https://github.com/qkast/api-documentation/blob/master/endpoints/widget/GET_widget_id.md)**

#### Channel

- **[<code>GET</code> channel](https://github.com/qkast/api-documentation/blob/master/endpoints/widget/GET_channels.md)**
- **[<code>GET</code> channel/:id](https://github.com/qkast/api-documentation/blob/master/endpoints/widget/GET_channel_id.md)**

## FAQ
### What do I need to know before I start using the API?
Got rust on your skills? No worries. Here are the docs you might need to get started:

- HTTPS protocol
- [REST software pattern][]
- Data serialization with [JSON][] (or see a [quick tutorial][])

### How do I connect to the qkast.com API?
Generally, reading any data is done through a request with the GET method. If you want our server to create, update or delete a given resource, POST or PUT methods are required on supported end points.

### What return formats do you support?
qKast API currently returns data in [JSON](http://json.org/ "JSON") format.

### What kind of authentication is required?
There is no authentication required right now.

### Is there a request rate limit?
Nope.

* [REST software pattern]: http://en.wikipedia.org/wiki/Representational_State_Transfer
* [JSON]: http://json.org
* [quick tutorial]: http://www.webmonkey.com/2010/02/get_started_with_json/
* [Register your application]: https://qkast.com/share?channel=1337
* [API Terms of Use]: https://cdn.rawgit.com/egfx/02afd9a1e3bebc667dd168a9690fafc6/raw/019163ad4be041a664698292e5a82174bb69a327/privacy.html
