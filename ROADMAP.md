# Roadmap

We currently cover **146 AWS services**. Below are the **91 services** we still need to add.

This list was built by comparing all **417 services available in boto3** against what awsmap already covers, then filtering out deprecated/sunset services and data-plane-only APIs that don't have inventoriable resources.

To contribute: pick a service, write a collector in `src/aws_inventory/collectors/`, and open a PR.

## Services to add

- **aiops** — AI Operations
- **appfabric** — App bundles, ingestions
- **appintegrations** — Event/data integrations
- **application-insights** — CloudWatch Application Insights
- **application-signals** — CloudWatch Application Signals
- **appstream** — AppStream 2.0 fleets, stacks, images
- **autoscaling-plans** — Auto Scaling plans
- **b2bi** — B2B Data Interchange profiles, transformers
- **bedrock-agent** — Agents, knowledge bases, data sources
- **bedrock-data-automation** — Data automation projects
- **chatbot** — Slack/Teams channel configs
- **cleanroomsml** — Clean Rooms ML models
- **codeconnections** — Source provider connections
- **connectcampaignsv2** — Connect outbound campaigns
- **connectcases** — Connect Cases domains, templates
- **controltower** — Landing zones, enabled controls
- **customer-profiles** — Connect Customer Profiles domains
- **databrew** — Glue DataBrew datasets, projects, recipes, jobs
- **dataexchange** — Data sets, revisions
- **datazone** — Domains, projects, environments
- **deadline** — Deadline Cloud farms, queues, fleets
- **docdb-elastic** — DocumentDB Elastic Clusters
- **drs** — Elastic Disaster Recovery
- **dsql** — Aurora DSQL clusters
- **emr-containers** — EMR on EKS virtual clusters
- **entityresolution** — Matching workflows, schema mappings
- **evs** — Elastic VMware Service environments
- **gameliftstreams** — GameLift Streams stream groups
- **greengrassv2** — Core devices, components, deployments
- **groundstation** — Ground Station configs, mission profiles
- **healthlake** — HealthLake FHIR datastores
- **internetmonitor** — Internet monitors
- **iot-managed-integrations** — IoT Managed Integrations
- **iotfleetwise** — IoT FleetWise campaigns, fleets, vehicles
- **iottwinmaker** — IoT TwinMaker workspaces, scenes, entities
- **iotwireless** — IoT Wireless devices, gateways, profiles
- **ivs-realtime** — IVS Real-Time stages, compositions
- **ivschat** — IVS Chat rooms, logging configs
- **kinesisanalyticsv2** — Managed Apache Flink applications
- **kinesisvideo** — Kinesis Video streams
- **launch-wizard** — Deployments
- **license-manager** — License configurations, grants
- **license-manager-user-subscriptions** — User-based subscriptions
- **mailmanager** — SES Mail Manager policies, rule sets
- **managedblockchain** — Managed Blockchain networks, nodes
- **mediapackage-vod** — MediaPackage VOD packaging groups, assets
- **mediapackagev2** — MediaPackage V2 channel groups, channels
- **medical-imaging** — HealthImaging datastores, image sets
- **mgn** — Application Migration Service
- **mpa** — Multi-party approval policies
- **mwaa-serverless** — MWAA Serverless environments
- **neptune-graph** — Neptune Analytics graphs
- **networkflowmonitor** — Network flow monitors
- **networkmonitor** — CloudWatch Network Monitor probes
- **oam** — Observability Access Manager links and sinks
- **odb** — Oracle Database on AWS
- **omics** — HealthOmics workflows, runs, stores
- **osis** — OpenSearch Ingestion pipelines
- **payment-cryptography** — Payment keys, aliases
- **pca-connector-ad** — PCA Connector for Active Directory
- **pca-connector-scep** — PCA Connector for SCEP
- **pcs** — Parallel Computing Service clusters
- **qbusiness** — Q Business applications, indices
- **qconnect** — Q Connect assistants and knowledge bases
- **rbin** — Recycle Bin retention rules
- **repostspace** — re:Post Private spaces
- **rolesanywhere** — IAM Roles Anywhere trust anchors, profiles
- **route53-recovery-control-config** — ARC clusters, control panels, routing controls
- **route53-recovery-readiness** — Readiness checks, recovery groups
- **route53globalresolver** — Global Resolver rules
- **route53profiles** — Route 53 Profiles
- **rum** — CloudWatch Real User Monitoring
- **s3control** — Access points, Storage Lens
- **s3outposts** — S3 on Outposts endpoints
- **s3tables** — S3 Tables table buckets
- **security-ir** — Incident response cases
- **servicecatalog-appregistry** — Applications, attribute groups
- **signer** — Signing profiles
- **ssm-contacts** — Contacts and escalation plans
- **ssm-quicksetup** — Quick Setup configurations
- **ssm-sap** — SAP applications
- **supplychain** — Supply Chain instances
- **timestream-influxdb** — Timestream for InfluxDB instances
- **tnb** — Telco Network Builder packages, networks
- **verifiedpermissions** — Policy stores, policies
- **wellarchitected** — Workloads, lenses, reviews
- **wickr** — Wickr networks
- **workmail** — Organizations, users, groups
- **workspaces-instances** — WorkSpaces Instances
- **workspaces-thin-client** — Thin Client environments, devices
- **workspaces-web** — Web portals, browser settings

## Note: **frauddetector** already in awsmap

**frauddetector** was put in maintenance mode by AWS on Nov 7, 2025. It still works but no longer accepts new customers. We may remove it in a future release.
