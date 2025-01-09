# Sports Data Lake
--

### Overview
This project creates an Amazon S3 bucket to store raw and processed data NBA player data. We then uploads sample NBA data (in JSON format) to our S3 bucket. From there we create an AWS Glue database and an external table for querying the data. Lastly, we leverage Amazon Athena for querying data stored in the S3 bucket.

### Architecture
[insert diagram]

Tooling and Services Used:
- **Cloud Provider**: AWS
- **Core Services**: Glue, Athena, S3
- **External API**: NBA Game API (SportsData.io)
- **Programming Language**: Python 3.x
- **IAM Security**:
  - Least privilege policies

### Future Enhancements
- Show message if a bucket does not exist
- Show error if data is not fetched successfully
- Create query to display where players with the most championships went t
- Automate data ingestion with AWS Lambda
- Add advanced analytics and visualizations (AWS QuickSight) school

### Pre-reqs
- free subscription to [sportsdata.io](https://sportsdata.io/)
- aws account

---
### References
1. [SportsDataIO API](https://sportsdata.io/developers/api-documentation/nba)
2. [Youtube Video](https://www.youtube.com/watch?v=RAkMac2QgjM)


