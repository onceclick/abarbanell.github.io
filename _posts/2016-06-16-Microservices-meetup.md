---
title: "Microservice Architecture"
description: "Presentation from the Lausanne Cloud Computing Meetup, 16-Jun-2016"
category: slides 
tags: [presentation, micro service architecture, cloud computing, agile]
flexslider: 
 - image: /assets/img/2016/06/16/microservices/Slide01.jpg
 - image: /assets/img/2016/06/16/microservices/Slide02.jpg
 - image: /assets/img/2016/06/16/microservices/Slide03.jpg
 - image: /assets/img/2016/06/16/microservices/Slide04.jpg
 - image: /assets/img/2016/06/16/microservices/Slide05.jpg
 - image: /assets/img/2016/06/16/microservices/Slide06.jpg
 - image: /assets/img/2016/06/16/microservices/Slide07.jpg
 - image: /assets/img/2016/06/16/microservices/Slide08.jpg
 - image: /assets/img/2016/06/16/microservices/Slide09.jpg
 - image: /assets/img/2016/06/16/microservices/Slide10.jpg
 - image: /assets/img/2016/06/16/microservices/Slide11.jpg
 - image: /assets/img/2016/06/16/microservices/Slide12.jpg
 - image: /assets/img/2016/06/16/microservices/Slide13.jpg
 - image: /assets/img/2016/06/16/microservices/Slide14.jpg
 - image: /assets/img/2016/06/16/microservices/Slide15.jpg
 - image: /assets/img/2016/06/16/microservices/Slide16.jpg
 - image: /assets/img/2016/06/16/microservices/Slide17.jpg
 - image: /assets/img/2016/06/16/microservices/Slide18.jpg
 - image: /assets/img/2016/06/16/microservices/Slide19.jpg
 - image: /assets/img/2016/06/16/microservices/Slide20.jpg
 - image: /assets/img/2016/06/16/microservices/Slide21.jpg
 - image: /assets/img/2016/06/16/microservices/Slide22.jpg
 - image: /assets/img/2016/06/16/microservices/Slide23.jpg
 - image: /assets/img/2016/06/16/microservices/Slide24.jpg
 - image: /assets/img/2016/06/16/microservices/Slide25.jpg
 - image: /assets/img/2016/06/16/microservices/Slide26.jpg
 - image: /assets/img/2016/06/16/microservices/Slide27.jpg
 - image: /assets/img/2016/06/16/microservices/Slide28.jpg
 - image: /assets/img/2016/06/16/microservices/Slide29.jpg
 - image: /assets/img/2016/06/16/microservices/Slide30.jpg
 - image: /assets/img/2016/06/16/microservices/Slide31.jpg
 - image: /assets/img/2016/06/16/microservices/Slide32.jpg
 - image: /assets/img/2016/06/16/microservices/Slide33.jpg
 - image: /assets/img/2016/06/16/microservices/Slide34.jpg
 - image: /assets/img/2016/06/16/microservices/Slide35.jpg
 - image: /assets/img/2016/06/16/microservices/Slide36.jpg
 - image: /assets/img/2016/06/16/microservices/Slide37.jpg
 - image: /assets/img/2016/06/16/microservices/Slide38.jpg
 - image: /assets/img/2016/06/16/microservices/Slide39.jpg
 - image: /assets/img/2016/06/16/microservices/Slide40.jpg
---


This is my presentation from the Lausanne Cloud Computing Meetup on 16-Jun-2016


<div class="flexslider">
	<ul style="margin-left = 0;" class="slides">
		{% for slides in page.flexslider %}
			<li>
				<img src="{{ slides.image }}" />
			</li>
		{% endfor %}
	</ul>					
</div>

You can [get the PDF here]({{ site.url }}/assets/pdf/Microservices-meetup-2016-06-16.pdf).


{% if page.flexslider %}
<!-- Google CDN Hosted jQuery  -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.0.2/jquery.min.js"></script>
<!-- Flexslider Library  -->
<script src="/assets/js/jquery.flexslider-min.js"></script>
<!-- Initialisation Code  -->
<script src="/assets/js/slider.js"></script>
{% endif %}

