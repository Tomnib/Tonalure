# ADR 0001: Initial research environment

## Status
Accepted

## Context
I am deciding the environment for initial testing and research. Originally I was going to just create python files for each component. After thinking about it more, I believe using Jupyter NoteBooks would be more ideal, allowing me to run line-by-line code executions and better visualize data. SageMaker studios offers a cloud hosted Jupyter environment that I am considered utilizing for this. 

## Decision
I will use use Jupyter Notebooks for the initial research stages of this project. It will be a locally hosted instance, which will allow me to avoid compute costs and work offline as needed. Model training will probably be done in the cloud environment. 

## Consequences
- Compute power dependent on local machine's resources (In this case, my "laplet").
- Harder time integrating with AWS resources
