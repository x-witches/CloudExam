# Comptia Cloud+  exam

# Table of Contents

<!-- MarkdownTOC lowercase_only_ascii="true" depth=3 autolink="true" bracket="round" -->

1. Given a scenario, analyze system requirements to ensure successful system deployment.
	1. Appropriate commands, structure, tools, and automation/orchestration as needed
	1. Platforms and applications
	1. Interaction of cloud components and services
		1. Network components
		1. Application components
		1. Storage components
		1. Compute components
		1. Security components
	1. Interaction of non-cloud components and services
	1. Baselines
	1. Target hosts
	1. Existing systems
	1. Cloud architecture
	1. Cloud elements/target objects
1. Given a scenario, execute a provided deployment plan
	1. Apply the change management process
		1. Approvals
		1. Scheduling
	1. Refer to documentation and follow standard operating procedures
	1. Execute workflow
	1. Configure automation and orchestration, where appropriate, for the system being deployed
	1. Use commands and tools as needed
	1. Document results
1. Given a scenario, analyze system requirements to determine if a Given testing plan is appropriate.
	1. Underlying environmental considerations included in the testing plan
		1. Shared components
		1. Storage
		1. Compute
		1. Network
		1. Production vs. development vs. QA
		1. Sizing
		1. Performance
		1. High availability
		1. Connectivity
		1. Data integrity
		1. Proper function
		1. Replication
		1. Load balancing
		1. Automation/orchestration
	1. Testing techniques
		1. Vulnerability testing
		1. Penetration testing
		1. Load testing
1. Given a scenario, analyze testing results to determine if the testing was successful in relation to Given system requirements.
	1. Consider success factor indicators of the testing environment
		1. Sizing
		1. Performance
		1. Availability
		1. Connectivity
		1. Data integrity
		1. Proper functionality
	1. Document results
	1. Baseline comparisons
	1. SLA comparisons
	1. Cloud performance fluctuation variables
1. Given a scenario, analyze sizing, subnetting, and basic routing for a provided deployment of the virtual network.
	1. Cloud deployment models
		1. Public
		1. Private
		1. Hybrid
		1. Community
	1. Network components
	1. Applicable port and protocol considerations when extending to the cloud
	1. Determine configuration for the applicable platform as it applies to the network
		1. VPN
		1. IDS/IPS
		1. DMZ
		1. VXLAN
		1. Address space required
		1. Network segmentation and microsegmentation
	1. Determine if cloud resources are consistent with the SLA and/or change management requirements
1. Given a scenario, analyze CPU and memory sizing for a provided deployment.
	1. Available vs. proposed resources
		1. CPU
		1. RAM
	1. Memory technologies
		1. Bursting and ballooning
		1. Overcommitment ratio
	1. CPU technologies
		1. Hyperthreading
		1. VT-x
		1. Overcommitment ratio
	1. Effect to HA/DR
	1. Performance considerations
	1. Cost considerations
	1. Energy savings
	1. Dedicated compute environment vs. shared compute environment
1. Given a scenario, analyze the appropriate storage type and protection capability for a provided deployment.
	1. Requested IOPS and read/ write throughput
	1. Protection capabilities
		1. High availability
		1. Failover zones
		1. Storage replication Regional
		1. Multiregional
		1. Synchronous and asynchronous
		1. Storage mirroring
		1. Cloning
		1. Redundancy level/factor
	1. Storage types
		1. NAS
		1. DAS
		1. SAN
		1. Object storage
	1. Access protocols
	1. Management differences
	1. Provisioning model
		1. Thick provisioned
		1. Thin provisioned
		1. Encryption requirements
		1. Tokenization
	1. Storage technologies
		1. Deduplication technologies
		1. Compression technologies
	1. Storage tiers
	1. Overcommitting storage
	1. Security configurations for applicable platforms
		1. ACLs
		1. Obfuscation
		1. Zoning
		1. User/host authentication and authorization
1. Given a scenario, analyze characteristics of the workload (storage, network, compute) to ensure a successful migration.
	1. Migration types
		1. P2V
		1. V2V
		1. V2P
		1. P2P
		1. Storage migrations
		1. Online vs. offline migrations
	1. Source and destination format of the workload
		1. Virtualization format
		1. Application and data portability
	1. Network connections and data transfer methodologies
	1. Standard operating procedures for the workload migration
	1. Environmental constraints
		1. Bandwidth
		1. Working hour restrictions
		1. Downtime impact
		1. Peak timeframes
		1. Legal restrictions
		1. Follow-the-sun constraints/time zones
1. Given a scenario, apply elements required to extend the infrastructure into a Given cloud solution.
	1. Identity management elements
		1. Identification
		1. Authentication
		1. Authorization
		1. Approvals
		1. Access policy
		1. Federation
		1. Single sign-on
	1. Appropriate protocols Given requirements
	1. Element considerations to deploy infrastructure services such as:
		1. DNS
		1. DHCP
		1. Certificate services
		1. Local agents
		1. Antivirus
		1. Load balancer
		1. Multifactor authentication
		1. Firewall
		1. IPS/IDS
1. Given a scenario, apply security configurations and compliance controls to meet Given cloud infrastructure requirements.
	1. Company security policies
	1. Apply security standards for the selected platform
	1. Compliance and audit requirements governing the environment
		1. Laws and regulations as they apply to the data
	1. Encryption technologies
		1. IPSec
		1. SSL/TLS
		1. Other ciphers
	1. Key and certificate management
		1. PKI
	1. Tunneling protocols
		1. L2TP
		1. PPTP
		1. GRE
	1. Implement automation and orchestration processes as applicable
	1. Appropriate configuration for the applicable platform as it applies to compute
		1. Disabling unneeded ports and services
		1. Account management policies
		1. Host-based/software firewalls
		1. Antivirus/anti-malware software
		1. Patching
		1. Deactivating default accounts

1. Given a scenario, apply the appropriate ACL to the target objects to meet access requirements according to a security template.
	1. Authorization to objects in the cloud
		1. Processes
		1. Resources
		1. Users
		1. Groups
		1. System
		1. Compute
		1. Networks
		1. Storage
		1. Services
	1. Effect of cloud service models on security implementations
	1. Effect of cloud deployment models on security implementations
	1. Access control methods
		1. Role-based administration
		1. Mandatory access controls
		1. Discretionary access controls
		1. Non-discretionary access controls
		1. Multifactor authentication
		1. Single sign-on

1. Given a cloud service model, implement defined security technologies to meet Given security requirements.
	1. Data classification
	1. Concepts of segmentation and microsegmentation
		1. Network
		1. Storage
		1. Compute
	1. Use encryption as defined
	1. Use multifactor authentication as defined
	1. Apply defined audit/ compliance requirements

1. Given a cloud service model, apply the appropriate security automation technique to the target system.
	1. Tools
		1. APIs
		1. Vendor applications
		1. CLI
		1. Web GUI
		1. Cloud portal
	1. Techniques
		1. Orchestration
		1. Scripting
		1. Custom programming
	1. Security services
		1. Firewall
		1. Antivirus/anti-malware IPS/IDS
		1. HIPS
	1. Impact of security tools to systems and services
		1. Scope of impact
	1. Impact of security automation techniques as they relate to the criticality of systems
		1. Scope of impact
1. Given a cloud service model, determine the appropriate methodology to apply Given patches.
		1. Scope of cloud elements to be patched
			1. Hypervisors
			1. Virtual machines
			1. Virtual appliances
			1. Networking components
			1. Applications
			1. Storage components
			1. Clusters
		1. Patching methodologies and standard operating procedures
			1. Production vs. development vs. QA
			1. Rolling update
			1. Blue-green deployment
			1. Failover cluster
		1. Use order of operations as it pertains to elements that will be patched
		1. Dependency considerations

	1. Given a scenario, apply the appropriate automation tools to update cloud elements.
		1. Types of updates
			1. Hotfix
			1. Patch
			1. Version update
			1. Rollback
		1. Automation workflow
			1. Runbook management
			1. Single node
			1. Orchestration
			1. Multiple nodes
			1. Multiple runbooks
		1. Activities to be performed by automation tools
			1. Snapshot
			1. Cloning
			1. Patching
			1. Restarting
			1. Shut down
			1. Maintenance mode
			1. Enable/disable alerts

1. Given a scenario, apply an appropriate backup or restore method.
	1. Backup types
		1. Snapshot/redirect-on-write
		1. Clone
		1. Full
		1. Differential
		1. Incremental
		1. Change block/delta tracking
	1. Backup targets
		1. Replicas
		1. Local
		1. Remote
	1. Other considerations
		1. SLAs
		1. Backup schedule
		1. Configurations
	1. Objects
		1. Dependencies
		1. Online/offline

1. Given a cloud-based scenario, apply appropriate disaster recovery methods.
	1. DR capabilities of a cloud service provider
	1. Other considerations
		1. SLAs for DR
		1. RPO
		1. RTO
		1. Corporate guidelines
		1. Cloud service provider guidelines
		1. Bandwidth or ISP limitations
		1. Techniques
		1. Site mirroring
		1. Replication
		1. File transfer
		1. Archiving
		1. Third-party sites

1. Given a cloud-based scenario, apply the appropriate steps to ensure business continuity.
	1. Business continuity plan
		1. Alternate sites
		1. Continuity of operations
		1. Connectivity
		1. Edge sites
		1. Equipment
		1. Availability
		1. Partners/third parties
		1. SLAs for BCP and HA

1. Given a scenario, apply the appropriate maintenance automation technique to the target objects.
	1. Maintenance schedules
	1. Impact and scope of maintenance tasks
	1. Impact and scope of maintenance automation techniques
	1. Include orchestration as appropriate
	1. Maintenance automation tasks
		1. Clearing logs
		1. Archiving logs
		1. Compressing drives
		1. Removing inactive accounts
		1. Removing stale DNS entries
		1. Removing orphaned resources
		1. Removing outdated rules from firewall
		1. Removing outdated rules from security
		1. Resource reclamation
		1. Maintain ACLs for the target object

1. Given a scenario, analyze defined metrics to determine the presence of an abnormality and/or forecast future needed cloud resources.
	1. Monitoring
		1. Target object baselines
		1. Target object anomalies
		1. Common alert methods/messaging
		1. Alerting based on deviation from baseline
		1. Event collection
	1. Event correlation
	1. Forecasting resource capacity
		1. Upsize/increase
		1. Downsize/decrease
	1. Policies in support of event collection
	1. Policies to communicate alerts appropriately

1. Given a scenario, determine the appropriate allocation of cloud resources.
	1. Resources needed based on cloud deployment models
		1. Hybrid
		1. Community
		1. Public
		1. Private
	1. Capacity/elasticity of cloud environment
	1. Support agreements
		1. Cloud service model maintenance responsibility
	1. Configuration management tool
	1. Resource balancing techniques
	1. Change management
		1. Advisory board
		1. Approval process
		1. Document actions taken
		1. CMDB
		1. Spreadsheet

1. Given a scenario, determine when to provision/ deprovision cloud resources.
	1. Usage patterns
	1. Cloud bursting
		1. Auto-scaling technology
	1. Cloud provider migrations
	1. Extending cloud scope
	1. Application life cycle
		1. Application deployment
		1. Application upgrade
		1. Application retirement
		1. Application replacement
		1. Application migration
		1. Application feature use
		1. Increase/decrease
	1. Business need change
		1. Mergers/acquisitions/divestitures
		1. Cloud service requirement changes
		1. Impact of regulation and law changes

1. Given a scenario, implement account provisioning techniques in a cloud environment to meet security and policy requirements.
	1. Identification
	1. Authentication methods
		1. Federation
		1. Single sign-on
	1. Authorization methods
		1. ACLs
		1. Permissions
	1. Account life cycle
	1. Account management policy
		1. Lockout
		1. Password complexity rules
	1. Automation and orchestration activities
		1. User account creation
		1. Permission settings
		1. Resource access
		1. User account removal
		1. User account disablement

1. Given a scenario, analyze deployment results to confirm they meet the baseline.
	1. Procedures to confirm results
		1. CPU usage
		1. RAM usage
		1. Storage utilization
		1. Patch versions
		1. Network utilization
		1. Application version
		1. Auditing enable
		1. Management tool compliance

1. Given a specific environment and related data (e.g., performance, capacity, trends), apply appropriate changes to meet expected criteria.

1. Given SLA requirements, determine the appropriate metrics to report.
	1. Analyze performance trends
	1. Refer to baselines
	1. Refer to SLAs
	1. Tuning of cloud target objects
		1. Compute
		1. Network
		1. Storage
		1. Service/application resources
	1. Recommend changes to meet expected performance/capacity
		1. Scale up/down (vertically)
		1. Scale in/out (horizontally)
	1.   Chargeback/showback models
		1. Reporting based on company policies
		1. Reporting based on SLAs
	1. Dashboard and reporting
		1. Elasticity usage
		1. Connectivity
		1. Latency
		1. Capacity
		1. Overall utilization
		1. Cost
		1. Incidents
		1. Health
		1. System availability
		1. Uptime
		1. Downtime

1. Given a scenario, troubleshoot a deployment issue.
	1. Common issues in the deployments
		1. Breakdowns in the workflow
		1. Integration issues related to different cloud platforms
		1. Resource contention
		1. Connectivity issues
		1. Cloud service provider outage
		1. Licensing issues
		1. Template misconfiguration
		1. Time synchronization issues
		1. Language support
		1. Automation issues

1.   Given a scenario, troubleshoot common capacity issues.
	1. Exceeded cloud capacity boundaries
		1. Compute
		1. Storage
		1. Networking
		1. IP address limitations
		1. Bandwidth limitations
		1. Licensing
		1. Variance in number of users
		1.  API request limit
		1. Batch job scheduling issues
	1. Deviation from original baseline
	1. Unplanned expansions

1. Given a scenario, troubleshoot automation/orchestration issues.
	1. Breakdowns in the workflow
		1. Account mismatch issues
		1. Change management failure
		1. Server name changes
		1. IP address changes
		1. Location changes
		1. Version/feature mismatch
		1. Automation tool incompatibility
		1. Job validation issue

1.   Given a scenario, troubleshoot connectivity issues.
	1. Common networking issues
		1. Incorrect subnet
		1. Incorrect IP address
		1. Incorrect gateway
		1. Incorrect routing
		1. DNS errors
		1. QoS issues
		1. Misconfigured VLAN or VXLAN
		1. Misconfigured firewall rule
		1. Insufficient bandwidth
		1. Latency
		1. Misconfigured MTU/MSS
		1. Misconfigured proxy
	1. Network tool outputs
	1. Network connectivity tools
		1. ping
		1. tracert/traceroute
		1. telnet
		1. netstat
		1. nslookup/dig
		1. ipconfig/ifconfig
		1. route
		1. arp
		1. ssh
		1. tcpdump
	1. Remote access tools for troubleshooting

1. Given a scenario, troubleshoot security issues.
	1. Authentication issues
		1. Account lockout/expiration
	1. Authorization issues
	1. Federation and single sign-on issues
	1. Certificate expiration
	1. Certification misconfiguration
	1. External attacks
	1. Internal attacks
	1. Privilege escalation
	1. Internal role change
	1. External role change
	1. Security device failure
	1. Incorrect hardening settings
	1. Unencrypted communication
	1. Unauthorized physical access
	1. Unencrypted data
	1. Weak or obsolete security technologies
	1. Insufficient security controls and processes
	1. Tunneling or encryption issues

1. Given a scenario, explain the troubleshooting methodology.
	1. Always consider corporate policies, procedures and impacts before implementing changes
		1. 1. Identify the problem
			1. Question the user and identify user changes to computer and perform backups before making changes
		1. 2. Establish a theory of probable cause (question the obvious)
			1. If necessary, conduct internal or external research based on symptoms
		1. 3. Test the theory to determine cause
			1. Once theory is confirmed, determine the next steps to resolve the problem
			1. If the theory is not confirmed, reestablish a new theory or escalate
		1. 4. Establish a plan of action to resolve the problem and implement the solution
		1. 5. Verify full system functionality and, if applicable, implement preventive measures
		1. 6. Document findings, actions and outcomes

<!-- /MarkdownTOC -->
