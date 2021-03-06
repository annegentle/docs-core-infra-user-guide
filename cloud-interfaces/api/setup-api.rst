.. _setup-api:

------------------------------
Preparing to use SDKs and APIs
------------------------------
If you have a Rackspace cloud account, you can use Rackspace APIs to interact with the cloud services you subscribe to.

The basic process is the same for all Rackspace APIs:

1. Collect parts needed for the request:

   * Obtain your account credentials (:kc-article:`API key <view-and-reset-your-api-key>` and account number, also called tenant ID) from the `Cloud Control Panel <https://mycloud.rackspace.com/>`__.
   * :rax-docs:`User your credentials to authenticate <auth/api/v2.0/auth-client-devguide/content/QuickStart-000.html>`, receiving a token and a service catalog as proof of success
   * In the :rax-docs:`service catalog <auth/api/v2.0/auth-client-devguide/content/Sample_Request_Response-d1e64.html>`, find the endpoint for the API to which you want to send a request.
   * Look up the :rax-api:`syntax of the API request <>`.

2. Assemble the request from its parts. Plug in the values you collected for your credentials, the API's endpoint, and any details (such as the ID of a server) specific to your configuration and your API request.
3. Send a well-formed request to the service's API endpoint.
4. Process the service's response.


Beyond this general process, the details vary depending on which service you are working with. For product-specific introductions to the SDKs and APIs relevant to specific core infrastructure products, see

* :ref:`cloudservers-api`
* :ref:`cloudnetworks-api`
* :ref:`cloudimages-api`
* :ref:`cloudblockstorage-api`
