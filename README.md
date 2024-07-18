# SystemdService-HealthCheck
Health checker for systemd unit which checks systemd status and also calls health check api

1. Make file executable : </br>
   `chmod +x Service-HealthChecker.sh`

2. Create Cron :  </br>
   `crontab -e` </br>
   `*/5 * * * * /path/to/Service-HealtchChecker.sh >> /path/to/Service-HealtchChecker.log 2>&1`
