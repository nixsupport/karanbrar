---
title: EMR and Step Functions
subtitle: BigData
layout: default
modal-id: 2
date: 2019-04-17
img: etl-step-functions-emr.png
thumbnail: etl-step-functions-emr-thumbnail.png
alt: EMR and Step Functions
project-date: April 2019
client: HOOPP
category: BigData
description: This solution was designed for ETL workflow. AWS StepFunction service was used to orchestrate the workflow. It gets triggered by a time based CloudWatch event rule. Once trigger, initial scripts are executed on EC2. On successful execution, a parallel job started within StepFunction. As a result of which EMR cluster is launched and then Step are executed. Appropriate status checks are implemented with "Wait" tasks in Step Functions. 

---
