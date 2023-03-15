---
title: "What is Amazon EKS Anywhere and how to deploy to vSphere"
date: 2023-03-10
draft: false
description: "Deploying EKS Anywhere in a Home Lab"
showDate : true
showDateUpdated : false
#showHeadingAnchors : true
#showPagination : false
showReadingTime : true
showTableOfContents : true
showTaxonomies : true 
showWordCount : true
showSummary : true
sharingLinks : false
Tags: ["aws", "eks-anywhere"]
summary: "EKS Anywhere is an AWS service that allows you to deploy and manage EKS clusters in on-premises environments."
---


## Introduction

EKS Anywhere is an AWS service that enables you to deploy and manage EKS clusters in on-premises environments. It uses Amazon EKS Distro (EKS-D), a publicly available Kubernetes distribution by AWS, which is also utilized by AWS-managed EKS. By deploying a combination of EKS and EKS Anywhere, you can maintain a consistent multi-cloud Kubernetes environment with similar toolsets.

With the EKS Connector, you can view all EKS and EKS Anywhere deployments in the AWS Console, as we'll demonstrate in this post.

For countries like New Zealand without an AWS Region (yet), EKS Anywhere is a great option for maintaining data onshore while utilizing one of the most popular container distros available. If an AWS Region is established in such countries, EKS Anywhere can help maintain data sovereignty and potentially bypass the US Cloud Act.

If you have a significant EKS presence in AWS but require specific security, application, or network requirements that are not available in the public cloud, EKS Anywhere could be a good solution for you.


### Subheading?

