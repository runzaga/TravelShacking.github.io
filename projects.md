---
layout: page
title: Favorite Projects
permalink: /projects/
---
## School Projects
- [Z-Wave Home Security and Automation](https://github.com/robzaga/Z-Wave) 
  - Implements Home Automation and Security on Raspberry Pi using Z-Wave Protocol
- [Virtual Machine](https://github.com/robzaga/VirtualMachine) 
  - Inputs Assembly Language as bit data into memory and executes multi-threaded functions
- [Motorola Microcontroller](https://github.com/Robzaga/MotorolaMicrocontroller)
  - Wrote Assembly Language commands to control PWM, Fuzzy Logic, etc.
- [Traffic Light](https://github.com/Robzaga/TrafficLight)
  - Used FPGA to emulate a traffic light with code written in Verilog


<div class="container">	
<div id="instagram-feed-demo" class="instagram_feed"></div>
</div>

<script src="https://www.jqueryscript.net/demo/Instagram-Photos-Without-API-instagramFeed/jquery.instagramFeed.js"></script>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script>
 (function($){
		$(window).on('load', function(){
			$.instagramFeed({
				'username': 'robzaga',
				'container': "#instagram-feed-demo",
				'display_profile': true,
				'display_biography': true,
				'display_gallery': true,
				'get_raw_json': false,
				'callback': null,
				'styling': true,
				'items': 36,
				'items_per_row': 6,
				'margin': 0.3
			});
		});
	})(jQuery);
