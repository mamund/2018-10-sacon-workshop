## Postal Code Story at BigCo, Inc.

We keep a validation table of postal codes. This is used by lots of other teams/services.

The data we keep includes the postal code, the country, state/province, and (where important) the city related to that code.

Typical work includes adding and editing entries and returning one or more codes based on filters (country, state/provice, city). The service also supports entering a postalcode value (e.g. 12345) and getting a true/false back to indicate whether that code exists in the system.


