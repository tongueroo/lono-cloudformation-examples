# Lono CloudFormation Examples

These are some basic CloudFormation template examples.  This examples are part of the Lono CloudFormation Framework Introduction blog tutorial series.

1. [Lono CloudFormation Framework Introduction Series Part 1: EC2 Instance](https://blog.boltops.com/2019/10/30/lono-cloudformation-framework-introduction-series-part-1-ec2-instance)
2. [Lono CloudFormation Framework Introduction Series Part 2: EC2, EIP, and Preview](https://blog.boltops.com/2019/11/05/lono-cloudformation-framework-introduction-series-part-2-ec2-eip-and-preview)

## Tutorial 1

[Tutorial 1 Source Code](tutorial-1)

Commands:

    gem install lono
    lono new infra
    cd infra
    lono blueprint new demo
    lono summary demo
    lono cfn deploy demo
    lono cfn delete demo

## Tutorial 2

[Tutorial 2 Source Code](tutorial-2)

Commands:

    lono cfn deploy demo

## Raw CloudFormation Tutorial Series

You may also be interested in the [Raw CloudFormation Examples](https://github.com/tongueroo/cloudformation-examples) from the [A Simple Introduction to AWS CloudFormation Series](https://blog.boltops.com/2017/03/06/a-simple-introduction-to-aws-cloudformation-part-1-ec2-instance).