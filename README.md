# AWS IP Ranges History Tracker

Amazon Web Services provides a list of IP Addresses used by their services through a published file available here [ip-ranges.json](https://ip-ranges.amazonaws.com/ip-ranges.json). They only provide the current listing, with no history of changes.

It is possible to subscribe to an SNS topic to receive a notification each time an update is released: [AWS IP address ranges notifications](https://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html#subscribe-notifications)

This repository keeps track of the changes on the main file ip-ranges.json and categorize the content of this file splitting it in many files for each type of IP (IPv4 and IPv6), for each service (S3, CloudFront, EC2, etc...) and for each region (us-east-1, eu-west-1, etc...).

This repository is *for informational purposes only*.
