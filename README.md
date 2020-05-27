
Filter
vRealize Operations REST API Examples
API
This collection is not linked to any API
Learn how to document your requests
Description

A collection of vRealize Operations REST APIs organized by use case. This collection is updated frequently and typically using the latest release of vRealize Operations.

Also now include are some examples for deploying a new vRealize Operations cluster using the CASA API. CASA stands for Cluster and Slice Administration. This API allows you to install and manage your cluster.

Authorization for the REST APIs are handled via OAuth and an API call is included that will request and store a token for the other REST calls. Be sure to set the included variables for your env. Basic auth is only used by the REST API "Run First" call.

Authentication for CASA uses basic and you will also need to get the master node thumbprint for some of these workflows.

Also, many of the REST calls have tests, which store additional information as part of a workflow. Be sure to set headers to send/rec payloads in JSON format, as the tests assume this format. Default for vROps API is XML so any post-tests will fail and any pre-tests provide env vars in JSON format.

Documentation

Documentation for the APIs can be found on the vROps appliance:

/suite-api for the REST APIs /casa/api-guide.html for the CASA REST APIs

Contributors:

John Dias, diasj@vmware.com Chris McClanahan, mcclanahanc@vmware.com Brandon Gordon, gbrandon@vmware.com, Kim Bottu @kim_bottu

