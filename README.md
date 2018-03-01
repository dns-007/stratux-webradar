# stratux-webradar
Simple Webclient for STRATUX to display Traffic in your area.
It filters all Planes to only the ones +-1000feet ablove or below you. 
It will show all Stratux Targets (ADSB and FLARM) with GPS position as a Plane on the Radar. The Targets that have no GPS, will be shown as circles and the Signal Strength is used to dertmine how close they are. Thicker circles means, the Targets get closer. 
Red Circle = Signal gets Stronger on a target +-1000ft of your hight
Green Circle = Signal gets weeker on a target +- 1000 ft of your hight
gray Circle = The Target sends no Altitude. Ticker line means it got closer from the first signal strength we got.


To install it, copy the content of src to the /var/www/ directory of the stratux

You can that open the radar screen in the URL http://192.168.10.1/radar.htm

Feedback is welcome!
