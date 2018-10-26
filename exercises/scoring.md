## Scoring Model for RESTful Microservices

Use this scoring system to determine the "cost" of your Microservice design/implementation

_NOTE: A lower score is better._

 * Process Score:
   * For each "dependent step" in your WSD, add 100
 * Description Score:
   * For each unique data name in your ALPS, add 1000
 * Scores for MS Type: 
   * Stateless = 10, 
   * Persistence = 100, 
   * Aggregator = 1000
 * Format Score: 
   * HTML = 1
   * Collection+JSON = 10
   * Siren or HAL = 100
   * JSON or XML = 1000
 * Stability Score:
   * Timeout, Bulkhead, Failfast = 10
   * Circuitbreaker, Steadystate, Handshaking = 1000
 * Bindability Score:
   * For each service you need to "bind" to your own, add 1000
 * Adaptability Score:
   * For each added data point, add 1 * your Format value
   * For each added action, add 10 * your Format value

ServiceCost =  Process + Description + MSType + Format + Stability + Bindability + Adaptability  
