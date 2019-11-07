# Lono CloudFormation Examples

These are some basic CloudFormation template examples.  This examples are part of the Lono CloudFormation Framework Introduction blog tutorial series.

* [Part 1: EC2 Instance](https://blog.boltops.com/2019/10/30/lono-cloudformation-framework-introduction-series-part-1-ec2-instance)
* [Part 2: EC2, EIP, and Preview](https://blog.boltops.com/2019/11/05/lono-cloudformation-framework-introduction-series-part-2-ec2-eip-and-preview)
* [Part 3: Configs Params Variables](https://blog.boltops.com/2019/11/06/lono-cloudformation-framework-introduction-series-part-3-configs-params-variables)
* [Part 4: Layering](https://blog.boltops.com/2019/11/07/lono-cloudformation-framework-introduction-series-part-4-layering)

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
    lono cfn delete demo

## Tutorial 3

[Tutorial 3 Source Code](tutorial-3)

Commands:

    lono cfn deploy demo
    lono cfn delete demo

## Tutorial 4

[Tutorial 4 Source Code](tutorial-4)

Commands:

    LONO_ENV=development lono cfn deploy demo-development --blueprint demo
    LONO_ENV=production  lono cfn deploy demo-production  --blueprint demo
    LONO_ENV=development lono cfn delete demo-development
    LONO_ENV=production  lono cfn delete demo-production

## Raw CloudFormation Tutorial Series

You may also be interested in the [Raw CloudFormation Examples](https://github.com/tongueroo/cloudformation-examples) from the [A Simple Introduction to AWS CloudFormation Series](https://blog.boltops.com/2017/03/06/a-simple-introduction-to-aws-cloudformation-part-1-ec2-instance).
