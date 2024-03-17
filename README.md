# EX280-Mock-Exam-02
EX280-Mock-Exam-02

Performance-Based Exam: Advanced OpenShift Administration

Instructions:

This exam consists of practical tasks that require advanced knowledge of OpenShift Container Platform.
Ensure that all configurations persist after a cluster reboot without intervention.
You have 3 hours to complete the exam.
Use the provided environment, including the web console, command-line interface, and product documentation as needed.

Task 1: Cluster Management

	1.1. Utilize the OpenShift command-line interface to create a new project named "advanced-mock-exam".

	1.2. Configure a network policy to enforce strict traffic rules within the "advanced-mock-exam" project, allowing only specific pod-to-pod communication.

	1.3. Implement a custom admission controller to enforce a policy that prohibits any pods running with root privileges across the entire cluster.

Task 2: Application Deployment

	2.1. Deploy a highly available MongoDB replica set with a minimum of 3 replicas and persistent storage using StatefulSets.

	2.2. Configure anti-affinity rules to ensure that MongoDB replicas are distributed across different nodes for resilience.

	2.3. Utilize the OpenShift web console to deploy a microservices architecture-based application using Helm charts, consisting of multiple interconnected services.

Task 3: Storage Management

	3.1. Implement a dynamic storage provisioning solution using the OpenShift Container Storage operator for automatic provisioning of storage resources based on application demand.

	3.2. Configure encryption-at-rest for all persistent volumes used by applications within the "advanced-mock-exam" project.

	3.3. Set up a scheduled backup mechanism for the MongoDB data, ensuring that backups are stored securely and are accessible for disaster recovery.

Task 4: Application Scalability and Reliability

	4.1. Implement a custom metric-based autoscaling solution for the WordPress deployment, scaling based on both CPU and memory utilization metrics.

	4.2. Set up PodDisruptionBudgets for critical applications to ensure high availability during maintenance operations.

	4.3. Configure application-level circuit breakers to handle failures gracefully and prevent cascading failures within the microservices architecture.

Task 5: Security and Compliance

	5.1. Implement role-based access control (RBAC) policies to enforce fine-grained access control within the "advanced-mock-exam" project, based on job roles and responsibilities.

	5.2. Utilize OpenShift Security Context Constraints (SCCs) to create a hardened security posture for containers, restricting privileged actions and capabilities.

	5.3. Set up continuous security scanning for container images using an integrated solution, ensuring compliance with security policies and standards.

Task 6: Monitoring and Logging

	6.1. Configure Prometheus and Grafana for advanced monitoring of cluster resources, including custom dashboards for tracking key performance indicators.

	6.2. Implement centralized logging using Fluentd and Elasticsearch, aggregating logs from all pods and services for comprehensive analysis and troubleshooting.

	6.3. Set up alerts and notifications based on predefined thresholds for critical application and infrastructure metrics, ensuring proactive monitoring and issue resolution.

Task 7: Disaster Recovery and High Availability

	7.1. Configure multi-zone replication for persistent storage resources to ensure data redundancy and disaster recovery capabilities across different availability zones.

	7.2. Implement a disaster recovery plan for the entire OpenShift cluster, including procedures for backup restoration, failover, and recovery in case of catastrophic events.

	7.3. Perform a live migration of critical workloads from one availability zone to another without service interruption, demonstrating high availability and resilience capabilities.
