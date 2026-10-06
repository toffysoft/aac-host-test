# aac-host-test

A static test page that frames the AI Avatar Concierge from another site, the way a customer's Host App does. It holds
no credentials: the Agent id and the Kiosk Token come from the URL fragment, which the page clears on load. Used for
Forviz's cross-site checks (platform#49, #59).

`reference-host.html` is the Reference Host page of the Avatar Frame (mock-partner-apis `reference-host`, unchanged), served
from this other site for the Windows Edge Kiosk run of platform#59.
