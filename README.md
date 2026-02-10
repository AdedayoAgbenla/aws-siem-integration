<h1>Centralized Logging &amp; Observability Implementation</h1>
<h3>AWS Enterprise Environment</h3>

<h2>Overview</h2>
<p>
  This repository documents the implementation of a centralized logging and observability framework across a multi-account
  and multi-region AWS environment. The solution ensures consistent log collection, secure storage, compliance-aligned retention,
  and real-time analysis using a private SIEM platform.
</p>

<hr/>

<h2>Key Responsibilities</h2>
<ul>
  <li>Enabled organization-wide, multi-region AWS CloudTrail with Insights for abnormal API activity detection</li>
  <li>Integrated CloudTrail, Lambda, ECS, and container logs into Amazon CloudWatch Logs for centralized collection</li>
  <li>Implemented log retention and lifecycle policies aligned with regulatory and audit requirements</li>
  <li>Deployed a private Amazon OpenSearch domain inside a VPC as the centralized SIEM platform</li>
  <li>Configured fine-grained access control and IAM-based authentication for secure log access</li>
  <li>Built log streaming pipelines using Kinesis Data Firehose with S3 backup for durability</li>
  <li>Integrated Lambda-based log transformation for normalization and metadata enrichment</li>
  <li>Restricted SIEM network access using security groups and private connectivity</li>
  <li>Validated centralized visibility for CloudTrail, Lambda, and container workloads</li>
</ul>

<hr/>

<h2>Tools &amp; Technologies</h2>
<ul>
  <li>AWS CloudTrail</li>
  <li>Amazon CloudWatch Logs</li>
  <li>Amazon OpenSearch Service</li>
  <li>Amazon Kinesis Data Firehose</li>
  <li>AWS Lambda</li>
  <li>Amazon S3 (Lifecycle &amp; Archival)</li>
  <li>AWS IAM</li>
  <li>AWS KMS</li>
</ul>

<hr/>

<h2>Impact</h2>
<ul>
  <li>Established centralized visibility across AWS accounts and regions</li>
  <li>Improved incident investigation and threat detection capabilities</li>
  <li>Enabled compliance-aligned log retention and archival</li>
  <li>Reduced operational risk through secure, private SIEM integration</li>
  <li>Strengthened security monitoring and audit readiness</li>
</ul>

<hr/>

<h2>Author</h2>
<p>
  <strong>Adedayo</strong><br/>
  AWS Cloud Architect | Cloud Security Specialist
</p>

<hr/>

<h2>Disclaimer</h2>
<p>
  All documentation is anonymized and does not contain confidential or proprietary information.
</p>
