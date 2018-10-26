## Discovery Exercise

In this exercise, you will publish your service to a central registry (in this workshop, that will be a whiteboard or wall in the training room) and you will also use that registry to "find and bind" to any external services _your_ service needs in order to complete it's task.

These are the steps to you need to complete for this exercise

 * If your service depends on others to function (e.g. you use other services), do the following _for each service_ you need to use:
   * Search the shared registry to locate one or more services that can supply what you need
   * Confirm you understand the vocabulary used by that service (ALPS)
   * Confirm the service supports the message format you need
   * Confirm the service uses the protocol you need (in this workshop all will use HTTP)
   * Retrieve the ALPS document (in this workshop, ask the other team for a copy or URL pointer)
   * Incorporate the binding into your service (in this workshop that means updating your Service Document to include eleents from the remote service's ALPS document
   * Confirm you have added the proper stability patterns for each added service binding
 * Publish your service to the shared registry using the following:
   * A unique identifier for your service
   * An ALPS URL to indicate your service vocabulary
   * A URL where all new services can _start_ (and learn all your functionality)
   * Take a token
* Optionally, update your WSD file to include the added service bindings

_Note: You may discover that some service you need is not listed in the registry. In this case, you should still publish your service and then continue to check the registry until the service you need appears. At that point, you need to go through the entire discovery process again (including publishing your service again). Repeat this until all service bindings are covered._

