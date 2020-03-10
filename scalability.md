---
title: Scalability
layout: landing
description: 'Grow your infrastructure as your business grows'
image: assets/images/scalability.png
nav-menu: true
has-page: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Summon servers to meet demand</h2>
		</header>
		<p>Many websites will use one big server for everything.  Why pay for something that's only going to be fully utilized during peak hours?  With our model, we spin up several small servers when traffic increases, then shut them down when things settle.  Not only is this cost effictive, it's safer.  One server out of 10 crashing is much less worrying than your only server crashing.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<div class="inner">
		<header class="major">
			<h3>Lets look at a real example</h3>
		</header>
		<img src="assets/images/scalability/ec2-cpu-1.png" alt="Graph showing CPU spike" data-position="center center" />
		<p>Here we see in increase in CPU usage on the two running web servers.</p>
		<img src="assets/images/scalability/ec2-cpu-2.png" alt="Graph showing addition servers booting up" data-position="center center" />
		<p>Before the servers max out at 100%, additional servers are brought online to handle demand.</p>
		<img src="assets/images/scalability/ec2-cpu-3.png" alt="Graph showing CPU normalize" data-position="center center" />
		<p>Traffic normalizes as we find a comfortable amount of computing power to handle the burst in traffic.</p>
		<img src="assets/images/scalability/ec2-cpu-4.png" alt="Graph showing servers shut down" data-position="center center" />
		<p>The traffic surge is over, terminate the idle servers.</p>
		<img src="assets/images/scalability/ec2-cpu-5.png" alt="Graph showing normal operation" data-position="center center" />
		<p>Return to normal operation, around 30% CPU usage.</p>
	</div>
</section>

<!-- Three -->
<section id="three">
    <div class="inner">
        <p>All of this occured in less than one hour.  The site went from two servers, to 10 servers, back down to three servers.  All without human interaction or interupted service.</p>
        <p>The client was billed for <em>minutes</em> of server usage, not hours, days or months.</p>
    </div>
</section>

</div>
