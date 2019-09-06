---
title: Infrastructure Pipeline
subtitle: DevOps
layout: default
modal-id: 3
date: 2018-11-16
img: infra-pipeline.png
thumbnail: infra-pipeline-thumbnail.png
alt: Infrastructure Pipeline
project-date: November 2018
client: iAdvisory
category: DevOps
description: This implementation allows deployment of CloudFormation templates using CodePipeline. Engineers check-in the templates in CodeCommit which triggers the Pipeline. In Build stage, template syntax is validated using cfn-lint followed by security validation using cfn-nag. It reports if permissions are too permissive and fails the build in that case. Next stage is called Approval where anyone from designed set of individuals reviews and approves the change. In Deploy stage, templates are pushed to S3 first and then deployed using CloudFormation as Nested Stacks.

---
