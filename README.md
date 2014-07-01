CLSlack
=======

This libray provides the fundamentals for interacting with the Slack API and webhooks.

API calls can be done by using the method factory and passing it the necessary options. either a ``Controller`` (responding to outgoing webhooks), specific console commands (direct API method access),
and of course the API methods themselves, which can be sent from any point in your code, returning the response from Slack directly.

[![Build Status](https://secure.travis-ci.org/cleentfaar/CLSlack.png)](http://travis-ci.org/cleentfaar/CLSlack)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/cleentfaar/CLSlack/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/cleentfaar/CLSlack/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/cleentfaar/CLSlack/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/cleentfaar/CLSlack/?branch=master)

**NOTE:** If your project uses the Symfony Framework, you may be better off getting the related bundle [here](https://github.com/cleentfaar/CLSlackBundle).


### What now?

Since this is only a library, the way you use it is up to you.
To get you started however, I've created some usage examples:

[Check out the examples](Resources/doc/usage.md)

To get a greater understanding of how the different classes work together, check out the more detailed documentation below:

- [Outgoing Webhooks](Resources/doc/outgoing-webhooks.md)
- [API methods](Resources/doc/api-methods.md)
- [API method transport](Resources/doc/api-method-transport.md)

Additionally, check out the [API documentation](https://api.slack.com/) of Slack itself to get a
better picture of what happens in the background.


## Contributors

- The guys at [Slack](https://slack.com/), for making an awesome product and very clean documentation.
