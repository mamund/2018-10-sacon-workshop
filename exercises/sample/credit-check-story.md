## Credit Check Story at BigCo, Inc.

We use an external Credit-Check service to run checks on new customers.

The service performs a single task: returning a credit score for each customer we pass in a request.  The service takes the following inputs:

 * companyname REQUIRED
 * address (street 1 & 2, city, state/province, postalcode, country) OPTIONAL

It returns a credit-score from 1 (the worst) to 10 (the best). If the company/address is not found, the service returns 0.




