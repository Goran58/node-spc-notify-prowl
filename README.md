## Siemens SPC Notify Prowl
Send events from Siemens SPC intrusion alarm to iPhone and iPad by Prowl notification service.

To be able to use this module you need to have:
- An account and an api key from [Prowl](http://www.prowlapp.com/)
- SPC Web Gateway from [Lundix IT](http://www.lundix.se/smarta-losningar). SPC Web Gateway is providing a generic open REST and Websocket interface to Siemens SPC intrusion system.

## Installation
      
	git clone https://github.com/Goran58/node-spc-notify-prowl
	cd node-spc-notify-prowl
	npm install
	
## Configuration

- Modify the settings in config.json according to your environment and Prowl api key
- Adapt the function manageSiaEvent() to the SIA-events you would like to be managed. Look in the SPC documentation for definitions of the SIA event types.

## Start
	./node-spc-notify-prowl.js
