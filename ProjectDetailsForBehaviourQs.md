
### Global DB Monitoring and Diagnostics
#### Goals
* Identify and remove pain points for current internal operations
*  Reduce noise in the Sev 2 tickets
  * Able to resolve tickets faster ( MTTR < 30 min for most tkts )
  * Quickly identify issues in the replication ( mean time < 15-20 minutes)


###  LSE 
#### Goals
* Auto recovery and Auto retry for different components affected during LSE
* Ability to access / report impact during/after LSE event

* Impact reported during an LSE as
**Availability : Number of MAZ cluster unavailable in the region
** Number of MAZ primary clusters unavailable
** Number of MAZ secondary clusters unavailable
** Lag : P99, P95, P90 mirror lag
** Dashboard for Instance Availability
** E2E completion metric for GDB operations.

* LSE Dashboard to follow during differnt kind of LSEs
* Measure resilency of our micro services and entities in different kind of events
  * We need a test infra to simulate different kind of LSEs
  * DDB outage
  * Network Partition separating an AZ
  * EC2 rack down
  * VM throttling, SN availability
 
  ### Security DDOS
  * 3 signals of malicious activity that we are particularly interested
     * Process Crashes
     * Connection Exhaustion
     * Networking Card Exhaustion ( pkt drops etc...)

  ### SOP Review
     * Review current SOPs interms of correctness and coverage of all possible scenarios
     * Create new SOPs for identified scenarios
     * Migrate existing SOPs to git based
     * Set up a process for some scenarios which impacted customer experience
     * Set up a process for oncall in case SOP was not helpful
     * Automate with SOP runner
 
  ### Onboarding and Ramp-Up Plan
     * 30 day ramp-up and boot camp
     * OnCall readiness in 60 days

  ### Parallel and Multi-Region Deployment
     * Reduce Time for Deployment
     * Small, Medium and Large Clusters
     * Reduction in the manual steps as part of deploying
     * Quick identification of any deployment issues through metrics
       

  
  


 
