# Lono CloudFormation Examples

These are some basic CloudFormation template examples.  This examples are part of the Lono CloudFormation Framework Introduction blog tutorial series.

1. [Lono CloudFormation Framework Introduction Series Part 1: EC2 Instance
](https://blog.boltops.com/2019/10/30/lono-cloudformation-framework-introduction-series-part-1-ec2-instance)

## Source Code and Commands

### Tutorial 1

Source code: [Tutorial 1](tutorial-1)

Commands:

    gem install lono
    lono new infra
    cd infra
    lono blueprint new demo
    lono summary demo
    lono cfn deploy demo
    lono cfn delete demo
