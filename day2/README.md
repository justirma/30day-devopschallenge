# NBA Game Day Notifications / Sports Alerts System
---

### Overview
This project is an alert system that sends real-time NBA game day score notifications to subscribed users via SMS/Email. Our API will fetch live NBA game scores, send an email or SMS to subscribers with score updates leveraging an EventBridge scheduler/job. I also ensured that the IAM roles had the least privelege necessary.

### Architecture
[insert diagram]

Tooling and Services Used:
- **Cloud Provider**: AWS
- **Core Services**: SNS, Lambda, EventBridge
- **External API**: NBA Game API (SportsData.io)
- **Programming Language**: Python 3.x
- **IAM Security**:
  - Least privilege policies for Lambda, SNS, and EventBridge.

### Future Enhancements
- Improved design of email UI 
- Selecting multiple sport types 
- Choosing teams

### Pre-reqs
- free subscription to [sportsdata.io](https://sportsdata.io/)
- aws account

---
### References
1. [SportsDataIO API](https://sportsdata.io/developers/api-documentation/nba)
2. [Amazon EventBridge Scheduler](https://docs.aws.amazon.com/eventbridge/latest/userguide/using-eventbridge-scheduler.html)
3. [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
4. [Amazon SNS](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)
5. [Amazon SNS supports automatic deletion of unconfirmed subscriptions](https://aws.amazon.com/about-aws/whats-new/2023/05/amazon-sns-automatic-deletion-unconfirmed-subscriptions/)
6. [Youtube Video](https://www.youtube.com/watch?v=09WfkKc0x_Q&t=1430s)


