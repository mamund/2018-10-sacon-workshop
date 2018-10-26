## Customer Story at BigCo, Inc.

We keep track of customers. Each customer has a unique identifier in the system. Right now that is a combination of the first three letters of their last name and the first few letters of their first name (enough to create a unique identifier in the system). We add a digit if adding the full first name does not result in a unique identifier in the system.

Data we include in a customer record includes name (first, middle, last), address (street 1 & 2, city, state/province, postal code, country), voicephone (work, mobile), SMSNumber, email (work, alternate). Each record has a status value (suspended, active, pending-review). We also track the date/time the record was created and each date/time it was updated. We keep copies of the records, even after they have been deleted.

Typical work on the customer records include creating, updating, deleting (only a supervisor can do this) as well as getting a list of all customers using various filters (status, by country, by state, by last name). 
