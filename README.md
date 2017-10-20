# Connect-to-MS-Dynamics-CRM
With this set of policies and OAuth-Client application template you can start integrate 
into the MS-Dynamics-CRM service. 

The MS-Dynamics-CRM Web-API is protected by OAuth 2.0 and requires a personalized access 
using the OAuth 2.0 AuthZ-Code flow. This template is using Azure Active Directory as the 
Identity-Provider and OAuth-Authorization server.

You more information and see it live please review our video-series using this asset 
in the Axway API-Management Youtube-Channel: https://www.youtube.com/channel/UCsRNLDnXvgtz6qsleSlVcqQ

## API Management Version Compatibilty
This artefact was successfully tested for the following versions:
- V7.5.3

## Install
- Import the Configuration-Set (XML-File) into your configuration set

- Configure the OAuth-Client-Application as registered in the Azure Active Directory

- Setup the policy: "MS Dynamics CRM API-Mgr Routing" as to be a routing policy for API-Manager

More information to come!

## Usage
```
To test that API, you can basically call the Dynamics-CRM OData Web-API. For instance like this:
https://<you-api-mgt-host>:8065/api/data/v9.0/accounts?$filter=accountnumber eq 'ABSS4G45'
```
  

## Bug and Caveats

```
To be completed
```

## Contributing

Please read [Contributing.md][contrib] for details on our code of conduct, and the process for submitting pull requests to us.

[contrib]: https://github.com/Axway-API-Management/Common/blob/master/Contributing.md

## Team

![alt text][Axwaylogo] Axway Team

[Axwaylogo]: https://github.com/Axway-API-Management/Common/blob/master/img/AxwayLogoSmall.png  "Axway logo"


## License
[Apache License 2.0](/LICENSE)
