# Azure-Code-First-Data

- Code first
- OSS
- Containerized

## ADF discoverability

- Bits we don't know unless we explore/deeply know the product
- Creates the opportunity for code first - lack of examples, how to do etc opens the opp too.
- There is a class of data engineers who want to do it code first / all in code. MSFT customers also prefer this too.

## Analytics solution areas

- Pipelines
- Transformation
  - "Transforms with gui can accelerate and constrain"
- Ad-hoc sql
- Visualisation

## Can we not do everything from Spark?

- Why would we not? Can I connect to Oracle?
- Never going to sell the GUI to the developer... but it's **not binary** - it's not dev or not a dev - its a skilling path, and everyone is on that path.
- Where is the tipping point - "innovative tasks where code first helps you move faster". Better decoupled components, better testing.

### How do you handle the edge case

- **They are always there** - and the tools can fall short. With code, we can solve all the problems, not the ones that have been solved for before.
- Is something extensible? This solves the problem. If you cant extend it, then it fails.
- _How extensible can ADF become to support a whole host of user stories - across the spectrum._

## Typical challenges with code

- How do we enforce/manage data governance?
  - Lineage?
- Logging
  
## Further reading

- [openmetadata.org](openmetadata.org)
- [greatexpectations.io](greatexpectations.io)

### Potential outputs

- Toolkit and recommendations for code-first data analytics
  - airflow? prefect?
- ADF as an orchestrator vs ADF as a data transformation value add ++ tool (MDF etc)
- Journey of evolution

## What are the code first options?

- SSIS
- Batch jobs on VM
- AKS, Dockerized jobs.
- Virtual envs, Python, docker, codespaces

## Next Steps -  document the motivations

- ADF issues - data quality, complex processing, etc
- Then > What is ADF giving us when we have this many coders?
- Example customers - challenges, opportunities
- We don't have an answer for a recommended code first product for data engineering
- Why did ADLA fail and what were the core challenges in ADFv1 that were addressed with v2?
- Competitive POV
