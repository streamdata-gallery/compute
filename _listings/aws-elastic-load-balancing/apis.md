---
name: AWS Elastic Load Balancing
description: Elastic Load Balancing automatically distributes incoming application
  traffic across multiple Amazon EC2 instances. It enables you to achieve fault tolerance
  in your applications, seamlessly providing the required amount of load balancing
  capacity needed to route application traffic.nElastic Load Balancing offers two
  types of load balancers that both feature high availability, automatic scaling,
  and robust security. These include thenbsp;Classic Load Balancernbsp;that routes
  traffic based on either application or network level information, and thenbsp;Application
  Load Balancernbsp;that routes traffic based on advanced application level information
  that includes the content of the request. The Classic Load Balancer is ideal for
  simple load balancing of traffic across multiple EC2 instances, while the Application
  Load Balancer is ideal for applications needing advanced routing capabilities, microservices,
  and container-based architectures. Application Load Balancer offers ability to route
  traffic to multiple services or load balance across multiple ports on the same EC2
  instance.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_ElasticLoadBalancing.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Servers
- Performance
- Compute
- Availability
- Amazon Web Services
created: "2018-03-10"
modified: "2018-03-10"
url: https://raw.githubusercontent.com/streamdata-gallery/compute/master/_listings/aws-elastic-load-balancing/apis.yaml
specificationVersion: "0.14"
apis: []
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/elbv2/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticloadbalancing/classicloadbalancer/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticloadbalancing/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---