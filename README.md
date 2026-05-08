# Weather App – Manual Deployment with Nginx on WSL

Built a weather application using HTML, CSS, and JavaScript that fetches real-time weather data from the OpenWeatherMap API. 
The project was manually deployed using Ubuntu (WSL) and Nginx to understand real-world web hosting, Linux server setup, and deployment workflow.

# Features:
- Search weather by city
- Real-time temperature data
- Humidity information
- Wind speed display
- API integration using fetch()
- Responsive UI
- Manual deployment using Nginx

# Project Workflow :
  
Browser
   ↓
Nginx Web Server
   ↓
HTML/CSS/JavaScript Files
   ↓
OpenWeatherMap API

# Manual Deployment steps
- clone repository  :
  git clone <repo-url>
  cd weather-app

- install ngnix :
  sudo apt update
  sudo apt install nginx -y

- start ngnix:
  sudo service nginx start

- deploy files:
  sudo cp -r ~/weather-app/* /var/www/html/

- access website :
  http://localhost

# Through this project, I learned:
- API integration using JavaScript fetch()
- Linux basics using Ubuntu WSL
- Git and GitHub workflow
- Nginx web server setup
- Manual deployment process
- How web servers serve frontend applications
