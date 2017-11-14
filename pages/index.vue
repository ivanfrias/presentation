<template>
  <div class="content">
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>So, can you start by introducing yourself, telling us your education ?</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:01 AM</span></div>
	  </div>
    </div>
  </div>
  
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>Sure, I'm Ivan, I've graduated on Computer Engineer at Escola Superior de Tecnologia e Gestão de Leiria in 2008. In 2012 took regular lectures on Agile Development, finishing a Post-graduation with success later on. On 2014 I got back to college to undertake a MsC on Mobile Computing, but didn't finished that yet..</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:02 AM</span></div>
    </div>
  </div>
  
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>OK. What was your first professional experience on IT ?</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:05 AM</span></div>
	  </div>
    </div>
  </div>
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>I started working professionally on 2008, creating .NET desktop apps for a smaller company near my hometown - Dinamogest. using WPF, WCF, Spring.Net, NHibernat and some other interesting technology. That was my focus at the time.</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:06 AM</span></div>
    </div>
  </div>
  
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>On your resumé I can see that you changed on March 2010...</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:10 AM</span></div>
	  </div>
    </div>
  </div>
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>Yes, from 2010 until 2013 I moved to Aveiro where worked for PT-Inovação. I ended up working with the customer, writing technical documentation, support & development of production applications. Later on 2013 I also provided some support on migration and testing of a product for an international company.</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:12 AM</span></div>
    </div>
  </div>
  
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>Right. And then you leave that position and started working for CarMed.. How's that spelled ?</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:15 AM</span></div>
	  </div>
    </div>
  </div>
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>That's CarMediaLab. From 2013 until July 2017 I worked for them. I've worked mostly as a solution developer constructing Java desktop&web and back-end applications to help them manager their fleets ( Automotive, EVs ) and their infrastructure as well as some custom tooling projects.</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:16 AM</span></div>
    </div>
  </div>
  
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>Oh Ok. Now, what are you doing currently?</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:17 AM</span></div>
	  </div>
    </div>
  </div>
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>Do you know Fuze ? They are a major UCaaS Voice and Collab provider. I was recruited July this year and because of my experience I was nominated as a technical leader. I am currently supporting .NET solutions and developing full-stack apps (back-end & front-end) using web technologies ( node.js, css, html, electron, you name it...)</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:17 AM</span></div>
    </div>
  </div>
  
  <div class="rightBalloon">
    <div class="talk-bubble tri-right border round right-in">
      <div class="talktext">
	    <p>We already know you, can ou enlighten us about your likings?</p>
		<div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:20 AM</span></div>
	  </div>
    </div>
  </div>
  
  <div class="talk-bubble tri-right border round left-in">
    <div class="talktext">
      <p>I am currently living with his wife in Ourém - PT where we have 3 cats. I am actively involved on cultural activities mostly musical and theatre projects. I have also some other hobbies specially mountain-bike riding, development, music composition and xbox playing. I also enjoy a good netflix series now and then.</p>
	  <div class="time"><span><img class="littleCheck"src="~/assets/check.png"></img>12:21 AM</span></div>
    </div>
  </div>
  
  </div>	
</template>


<script>
  export default {
    layout: 'default'
  }
</script>

<style>

.border{
  border: 8px solid #666;
}

.talktext{
  padding: 1em;
  text-align: left;
  line-height: 1.5em;
}
.talktext p{
  /* remove webkit p margins */
  -webkit-margin-before: 0em;
  -webkit-margin-after: 0em;
}

.tri-right.border.left-in:before {
	content: ' ';
	position: absolute;
	width: 0;
	height: 0;
  left: -40px;
	right: auto;
  top: 30px;
	bottom: auto;
	border: 20px solid;
	border-color: #666 #666 transparent transparent;
}
.tri-right.left-in:after{
	content: ' ';
	position: absolute;
	width: 0;
	height: 0;
  left: -20px;
	right: auto;
  top: 38px;
	bottom: auto;
	border: 12px solid;
	border-color: lightyellow lightyellow transparent transparent;
}


.tri-right.border.right-in:before {
	content: ' ';
	position: absolute;
	width: 0;
	height: 0;
    left: auto;
	right: -40px;
    top: 30px;
	bottom: auto;
	border: 20px solid;
	border-color: #666 transparent transparent #666;
}
.tri-right.right-in:after{
	content: ' ';
	position: absolute;
	width: 0;
	height: 0;
    left: auto;
	right: -20px;
    top: 38px;
	bottom: auto;
	border: 12px solid;
	border-color: lightyellow transparent transparent lightyellow;
}

.round{
  border-radius: 10px;
	-webkit-border-radius: 10px;
	-moz-border-radius: 10px;
}

.content {
 background-color: rgba(255, 255, 255, 0.15);
}

.littleCheck {
 width: 10px;
 height: 10px;
}

.time {
  margin-top: 20px;
  font-size: 10px;
  font-style: italic;
  font-weight: bold;
}
.talk-bubble {
	margin: 40px;
  display: inline-block;
  position: relative;
	width: 200px;
	height: auto;
	background-color: lightyellow;
}

.rightBalloon {
  float: right;
}

</style>
. Provided