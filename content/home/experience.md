+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = "A chronological view of my roles across the healthcare and cloud automation space."

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "Cloud/DevOps Engineer"
  company = "MSD International GmbH (Singapore)"
  company_url = "https://www.msd.com/"
  location = "Singapore"
  date_start = "2023-10-01"
  date_end = ""
  description = """
  * Architected and deployed Amazon Security Lake across three AWS Organizations (2500+ accounts, six regions) as primary engineer using Terraform and CI/CD pipelines, achieving 47% infrastructure cost reduction. Work featured in AWS re:Invent 2025 breakout session (SEC347). 
  * Developed Agentic AI POC using LangChain and Claude 3.7 Sonnet to automate security analytics on 100+TB of OCSF data, reducing time-to-insight from a full-day to 30 minutes. 
  * Built self-service AWS DRS automation using GitHub Actions and CloudFormation, with org-level IAM roles. Reduced multi-step deployments to single-form automation across 35 production accounts. 
  * Built POC for automated testing using Robot Framework and GitHub Actions for AWS DRS Agent validation, addressing gaps when vulnerability scans caused service outages by shutting down agents.
  * Resolved AWS-ServiceNow API integration issues for account provisioning, reducing deployment time by 60% for 75+ production accounts.
  * Led 3-person team to migrate 13 Jenkins pipelines to GitHub Actions in 1 month, before company deprecation deadline. Onboarded junior team to Ansible and GitHub Actions within 4 days.
  * Developed Python automation tools using boto3 to enforce RDS compliance policies, automatically detecting, backing up, and cleaning non-compliant databases. 
  """

[[experience]]
  title = "Experience Design Strategist"
  company = "MSD International GmbH (Singapore)"
  company_url = "https://www.msd.com/"
  location = "Singapore"
  date_start = "2023-03-01"
  date_end = "2023-10-01"
  description = """
  * Designed high-fidelity iOS/web prototypes using Figma for manufacturing digitalization, reducing 
  technician task time by 80%.
  * Facilitated 3+ design thinking workshops with 30+ participants each, improving cross-functional 
  collaboration between IT and business teams. 
  """

[[experience]]
  title = "ServiceNow Platform Engineer"
  company = "MSD International GmbH (Singapore)"
  company_url = "https://www.msd.com/"
  location = "Singapore"
  date_start = "2022-07-01"
  date_end = "2023-02-01"
  description = """
  * Developed ServiceNow configurations for CMDB and HR application modules, and conducted peer/code reviews and unit tests across 5 ServiceNow application modules such as GSWD and StS workstreams.
  * Deployed update sets from dev to test environments, and updated configuration specification documents for UAT IQs in compliance with SDLC
  """

[[experience]]
  title = "Product Development Intern"
  company = "Interlinked AB"
  company_url = "https://www.interlinked.care/"
  location = "Stockholm, Sweden"
  date_start = "2021-01-01"
  date_end = "2022-01-01"
  description = """
  * Forecasted global demand of IV tubes across 42 different countries, resulting in data-driven insights for the company’s market expansion strategy. 
  * Co-developed a regulatory strategy for the US market, adapting ISO13485 to 21 CFR Part 820 standards and generating FDA Q-Submission documents for a 510(k) application.
  """
  
+++
