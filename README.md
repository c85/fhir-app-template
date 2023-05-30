# Cerner SMART on FHIR Template
This repo contains the minimum files you'll need for creating a Cerner SMART on FHIR app.<br>
Note: if your app privacy is set to <b>confidential</b>, please use the launch-confidential.html template

## Launching your FHIR app:
Use the following url structure to launch your app:

### U.S. Nonproduction
```
https://smart.sandboxcerner.com/smart/{tenant_id}/apps/{application_id}/?PAT_PersonId={person_id}&username={username}
```
### U.S. Production
```
https://smart.cerner.com/smart/{tenant_id}/apps/{application_id}/?PAT_PersonId={person_id}&username={username}
```
Where:
* tenant_id = Your Cerner Tenant (e.g., Cerner Sandbox = ec2458f2-1e24-41c8-b71b-0e701af7583d)
* application_id = Your App ID
* person_id = The Cerner Person ID
* username = Your Cerner Login ID (e.g., Cerner Sandbox = portal)