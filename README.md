# Useful Articles and Publishings about Cloud Computing

## Why You Should Use Continuous Integration and Continuous Deployment
https://css-tricks.com/continuous-integration-continuous-deployment/

## Continuous integration vs. continuous delivery vs. continuous deployment
https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment

## AWS EIP (Elastic IP)
Important AWS IP configuration, when it's configured we make sure that the provided IP is not going to be changed
[AWS EIP Reference](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)

## If your servers have no internet access it's probably because...
- You created the internet gateway but forgot to attach it to your VPC
- You placed your NAT Gateways inside private subnets with no routes to the outside world
- You have a missing route in your routing table
- You created a routing table but forgot to associate your subnet(s) with it.
[Route Tables Overview](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html)
[Route Table Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-route-table.html)
[Route Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-route.html)
[Subnet Route Table Association Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-subnet-route-table-assoc.html)

## AWS Cloud Formation Outputs
[Outputs Documentation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/outputs-section-structure.html)
[Join Function](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-join.html)
[Substitutes](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-sub.html)

## Understanding Security Groups
[Security Groups Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-ec2-security-group.html)
[Security Group Rules Reference](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/security-group-rules-reference.html)