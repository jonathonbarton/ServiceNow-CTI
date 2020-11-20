# ServiceNow-CTI
Custom ServiceNow CTI Processing to hooks the New Call module

This is a Business Rule that was created in early 2015 for ServiceNow Dublin version.

You can use the included concepts for integrating Computer Telephony Integration (which was available in cti.do at the time) to integrate with a softphone package that can pass the CallerID data to a browser to open a new browser tab or window on the Service Desk Agent's PC that has pre-filled a New Call Record if there is a match in sys_user for the Caller ID record. 

The original implementation used Shoretel as the IP phone software providing the CallerID data in a URL-encoded format.
