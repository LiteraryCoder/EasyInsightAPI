The Easy Insight API
====================

This is a REST-style API that uses JSON for serialization and basic authentication for user access.


Making a request
----------------

All URLs start with `https://'

Authentication
----------------

You'll need to use HTTP Basic Authentication for your integrations (OAuth is in the roadmap). You can either use your username and password or more securely, your key and secret key found under your User Profile in the Easy Insight user interface.

Handling Errors
----------------
If Easy Insight is having server problems, you'll receive a 5XX error.

Available APIs
----------------
* [Reports](https://github.com/easyinsight/EasyInsightAPI/blob/master/sections/reports.md)