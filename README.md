# DefaultApplication-config

http://HOST:PORT/hitcount

## Potential Parameters
Select a method of execution
- Servlet instance variable : selection=SRV
- Session state (create if necessary) : selection=SS2
- Existing session state only : selection=SS1

Namespace lookup method for EJB
- Global Namespace : lookup=GBL
- Local Namespace : lookup=LCL

Transaction type
- None : trans=NTX
- Commit : trans=CMT
- Rollback : trans=RLB

Don't select 'Enterprise Java Bean (CMP)' but other radio button options should work successfully.

<br>Select - Deploy and run your application
<br>Source repo : https://na.artifactory.swg-devops.com/artifactory/hyc-wassvt-team-maven-virtual
<br>Config repo : https://github.com/Paris-SVT-org/DefaultApplication-config
