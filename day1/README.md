# Weather Collection System

### Overview
By leveraging the openweatherAPI I was able to get and post weather updates onto my dashboard according to the locations I've specificied. A new S3 bucket is created if one does not exist, then we fetch weather data for the Philadelphia, Seattle, New York. We display the temperature, feels like, humidity levels, and any notes the weather app has posted regarding expected conditions.

### Architecture


Services Used:
Language: Python 3.x
Cloud Provider: AWS (S3)
External API: OpenWeather API
Dependencies:
- boto3 (AWS SDK)
- python-dotenv
- requests

### Future Enhancements
- Deploying a UI with the dashboard visuals

### Pre-reqs
- AWS account 
- openweatherAPI account

### References
1. [Youtube video](https://www.youtube.com/watch?v=A95XBJFOqjw)