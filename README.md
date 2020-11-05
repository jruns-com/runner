# runner
Runner for applications wroted in many programming languages

every minute:
  
    cron.sh

service

    start.sh
    stop.sh

app-runner

    install.sh
    unistall.sh
    upgrade.sh


1. Script cron start

NEW
2a. If first time, if repo not exist
    
    clone
 
3a. if new deploy, if is not working (status)
        
    install.sh
    start.sh
    
    
EXIST
2b. every minute ask git repository for new code
  
    pull
    
3b. if updated, deploy:

    stop.sh
    update.sh
    start.sh
