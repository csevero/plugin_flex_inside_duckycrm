# Flexercise #3 Plugin & CRM Wireframe

Flex Plugin & CRM wireframe for Flexercise #3

## Installation & Startup

Make sure you have the [Flex Plugins CLI](https://www.twilio.com/docs/flex/developer/plugins/cli) installed.

```
cd plugin-feathercorp-fx3-crm-frame/
npm install
twilio flex:plugins:start
```

Open [http://localhost:3000](http://localhost:3000) and login to Flex.

Then open the CRM wireframe at:
[http://localhost:3000/crm.html](http://localhost:3000/crm.html)

_Note that the code is intentionally incomplete and outbound calls do not work out of the box. To fix this, a phone number needs to be set in [FeathercorpPlugin.js](src/FeathercorpPlugin.js#L34)._
