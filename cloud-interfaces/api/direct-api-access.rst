.. _direct-api-access:

-----------------
Direct API access
-----------------
Each of our cloud services exposes an API which can be leveraged for
low-level integration with the service.
Rackspace APIs,
like OpenStack APIs,
are Representational State Transfer (REST) APIs,
meaning they are is logically
structured, stateless, and scalable (among other properties).

For most use cases, we recommend
working with the guidance of an SDK
rather than integrating directly with an API.
In the
:rax-dev:`Developer Center <docs>`,
we have documented basic
functions for many APIs in many popular programming languages in
quickstart guides. However, knowing the API
structure and being able to make direct, manual calls to the API is a
powerful tool for understanding and managing the Rackspace Cloud
infrastructure.

The API Developer Guide for each service is published in
:rax-docs:`our technical documentation collection <>`;
the same API operations are also listed
in a
combined
:rax-api:`API cross-reference <>`.

Some of the most common ways to directly interact with APIs are:

* Command line tools,
  such as
  `cURL <http://curl.haxx.se/>`__

* Browser extensions,
  such as
  `Postman for Chrome <https://www.getpostman.com/>`__

* Utilities for specific operating systems,
  such as those listed in your app store or directory
  under *REST client*

For each service that offers a public API,
Rackspace publishes at least two technical documents:

* :rax-docs:`API developer guide <>`:
  reference material *describing* API requests and sample responses

* :rax-docs:`API getting started guide <>`:
  tutorial material *demonstrating* simple interactions
  with the API

For most APIs, we also publish
:rax-docs:`API Release Notes <>`,
*announcing* changes to the API.

We publish these API documents primarily to support readers who are
already experienced with RESTful APIs in other contexts and
are seeking details specifically about Rackspace's APIs.
We don't publish a beginner-level API tutorial.
However, REST is widely used and introductory material is
readily available.
If you wish to work with our APIs and this would be your first
experience with RESTful APIs,
begin with :ref:`setup-api`.
