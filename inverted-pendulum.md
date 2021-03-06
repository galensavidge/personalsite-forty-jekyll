---
layout: project
title: Inverted Pendulum Bot
description: 'A configurable, autonomous Segway-like robot.'
image: assets/images/pendulum-bot-banner.jpg
nav-menu: false
github-url: 'https://github.com/galensavidge/inverted-pendulum-bot'
---

<section id="about">
	<div class="inner">
		<div class="row">
			<div class="9u 12u$(medium)">
				<header class="major">
					<h2>About</h2>
				</header>
				<p>The inverted pendulum is a classic feedback control problem. The coupled physical system exhibits complex behavior which can make it difficult to control. In this project I aim to tackle the problem from the ground up, using a derived kinematic model to simulate the effects of different feedback control techniques on the system. Eventually, I will build and program an inverted pendulum bot from scratch.</p>
			</div>
			<div class="3u$ 12u$(medium)" align="right">
				<header class="major">
					<h2>Source Code</h2>
				</header>
				<a href="{{ page.github-url }}" target="_blank">GitHub</a>
			</div>
		</div>
	</div>
</section>

<section id="simulation">
	<div class="inner">
		<header class="major">
			<h2>Simulation</h2>
		</header>
		<div class="row">
			<div class="8u 12u$(medium)">
				<p>A proof-of-concept Matlab simulation shows that two nested PID controllers can successfully drive the robot to a desired position.</p>
			</div>
			<div class="4u$ 12u$(medium)">
				<span class="image fit"><img src="assets/images/inverted-pendulum-side.gif" alt="assets/images/inverted-pendulum-thumb.PNG" /></span>
			</div>
		</div>
	</div>
</section>

<section id="robot">
	<div class="inner">
		<header class="major">
			<h2>Robot</h2>
		</header>
		<div class="row">
			<div class="8u 12u$(medium)">
				<p>The robot itself uses an Arduino Nano and other off-the-shelf parts. An on-board IMU package provides a way to measure orientation while high-speed continuous rotation servos allow for easy control of the robot's wheel speeds. The parts for the chassis are laser cut acrylic.</p>
			</div>
			<div class="4u$ 12u$(medium)">
				<span class="image fit"><img src="assets/images/pendulum-bot.jpg" alt="" /></span>
			</div>
		</div>
	</div>
</section>