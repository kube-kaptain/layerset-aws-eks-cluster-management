# Layerset AWS EKS Cluster Management

Kaptain layerset combines the layer with full build configuration for AWS EKS
cluster management projects and the github flow strict layer.

Composes these layers in order:

1. **layer-github-flow-strict** - strict GitHub flow quality enforcement
2. **layer-aws-eks-cluster-management** - EKS cluster yaml generation,
   pre/post build validation, docker build orchestration via the
   `postVersionsAndNaming` hook

## Documentation:

1. [Layer AWS EKS Cluster Management](https://github.com/kube-kaptain/layer-aws-eks-cluster-management#layer-aws-eks-cluster-management): Docs for setting up a build using this layerset or the layer directly
2. [Image AWS EKS Cluster Management](https://github.com/kube-kaptain/image-aws-eks-cluster-management#image-aws-eks-cluster-management): Docs on how to use the image that this layerset/layer builds
