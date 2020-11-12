RPO: recovery point objective. How much of data loss you are willing to accept in terms of disaster (high rpo is bad, low is good)
RTO: recovery time objective. The downtime you app has to face to recover from the disaster (high rto is bad, low is good)

## DR Strategies (ranked below in slower/higher to faster/lower rto and rpo. Cost increases from up to down in list)
- Backup and restore: take backups periodically and store from last checkpoint after disaster
- Pilot light: A small version of app (some services eg db) is always running in the cloud. Useful for critical core (pilot light) 
- Warm standby: A full system is up and running but at the minimum size, upon disaster we scale it to production load
- Hot site/multi site approach: Full production scale is always running
