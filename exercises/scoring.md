## Scoring Model for RESTful Microservices

Use this scoring system to determine the "cost" of your Microservice design/implementation

_NOTE: A lower score is better._

<!--
 * Process Score:
   * For each "dependent step" in your WSD, add 100
-->
 * Description Score:
   * For every data point, add 10
   * For every action, add 100
   * For each unique data name (not found in Schema.org), add 1000
 * Scores for MS Type: 
   * Stateless = 10, 
   * Persistence = 100, 
   * Aggregator = 1000
 * Format Score: 
   * HTML = 1
   * Collection+JSON = 10
   * Siren or HAL or Atom or OData = 100
   * JSON or XML = 1000
 * Stability Score:
   * Timeout, Bulkhead, Failfast = 100
   * Circuitbreaker, Steadystate, Handshaking = 1000
 * Bindability Score:
   * For each service you need to "bind" to your own, add 1000
 * Adaptability Score:
   * For each added data point, add 1 * your Format value
   * For each added action, add 10 * your Format value

ServiceCost =  Process + Description + MSType + Format + Stability + Bindability + Adaptability  
