# Daily Python Coding Challenge 🚀

**Welcome to my 100 Days of Python + AWS streak!**  
*Started: November 15, 2025* | *Goal: 1 challenge/day for 100 days* | *Current Streak: 0 days*  

I'm a self-taught AWS Cloud Practitioner (exam booked Dec 2025) building automation skills through daily Python challenges. Focus: **boto3 for AWS tasks, data structures, APIs, and scripting**. No fluff — just code, explanations, and runtime wins.  

**Why?** To master Python for cloud ops (e.g., automating EC2 starts, parsing CUR costs). Track my progress here + on LinkedIn (#100DaysOfCode).  

**Streak Rules:**  
- 1 problem/day (LeetCode-style or AWS practical).  
- Commit code + explanation.  
- Tie to AWS where possible (boto3 scripts).  
- If I miss? Reset streak — accountability over perfection.  

## Streak Log 📊

| Day | Date | Challenge | Description | AWS Tie-In | Runtime/Notes | Code Link |
|-----|------|-----------|-------------|------------|---------------|-----------|
| **0** | Nov 15, 2025 | Repo Setup | Initialized repo + README. | N/A | Streak begins! | [setup.py](https://github.com/sebhidalgo-ops/daily-code/blob/main/day00-setup.py) |
| **1** | Nov 16, 2025 | List S3 Buckets | Write script to list all S3 buckets + sizes using boto3. | S3 automation (from my cost-calculator project). | <1s for 10 buckets. Handle pagination. | [day01_s3_list.py](day01_s3_list.py) |
| **2** | Nov 17, 2025 | EC2 Status Check | Automate EC2 instance status check + start/stop by tag. | EC2 ops (inspired by two-tier-aws-project). | Use tags like "env=dev". | [day02_ec2_check.py](day02_ec2_check.py) |
| **3** | Nov 18, 2025 | Parse CUR CSV | Read CUR export CSV → top 3 services by cost. | CUR cost analysis (from cost-calculator). | Pandas for speed. | [day03_cur_parse.py](day03_cur_parse.py) |
| **4** | Nov 19, 2025 | Lambda Deploy Helper | Script to zip + upload code to Lambda via boto3. | Serverless (ties to ebookproject Lambda). | Error handling for IAM. | [day04_lambda_zip.py](day04_lambda_zip.py) |
| ... | ... | ... | ... | ... | ... | ... |

*(Add rows daily — use GitHub's table editor for ease.)*

## How to Run Challenges
1. Clone: `git clone https://github.com/sebhidalgo-ops/daily-code.git`  
2. Install: `pip install boto3 pandas` (or use AWS CLI creds).  
3. Run: `python dayXX_challenge.py`  
4. AWS Setup: Set `AWS_ACCESS_KEY` + `AWS_SECRET_KEY` env vars (or ~/.aws/credentials).  

## Tools & Resources
- **Python**: 3.12+  
- **Libs**: boto3, pandas, requests  
- **Inspo**: LeetCode, AWS Docs, freeCodeCamp  
- **Trackers**: [Streak Counter](https://streaks.app) | LinkedIn Posts  

## Progress Badge 🏆
![Python Streak](https://github.com/sebhidalgo-ops/daily-code/actions/workflows/streak.yml/badge.svg) *(Add GitHub Action later for auto-badge.)*

**Join the Streak?** Fork this repo, share your Day 1 below. Let's build cloud skills together!  

#100DaysOfCode #Python #AWS #DailyCoding  
*Last Updated: Nov 15, 2025*
