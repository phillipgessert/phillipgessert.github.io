---
layout: page
title: Contact
permalink: /contact/
---
The best way to contact me is by [email](mailto:phillip@gessertbooks.com). I'm very responsive and usually reply within one working day.
If you've got a finished manuscript, please feel free to include it with your message---it will make it easier to discuss your project, and is usually the first thing I ask for. Your manuscript is kept completely private and is not shared with anyone.
I don't discuss project details by phone, IM or Skype. No exceptions, please don't insist.


<form action="https://formspree.io/phillip@gessertbooks.com"
	method="POST">
	<h1>Contact Form</h1>
	<div class="row">
		<label for="name">Name:</label>
		<input type="text" name="name" required>
		<label for="_replyto">Email:</label>
		<input type="email" name="_replyto" required>
	</div>
	<div class="row">
		<label for="title">Book Title:</label>
		<input type="text" name="title">
		<select name="type">
			<option value="wc-null">Word Count</option>
			<option value="sub-80">Under 80k</option>
			<option value="80-160">80,001-160,000</option>
			<option value="160-240">160,001-240,000</option>
			<option value="over-240">Over 240k</option>
		</select>
		<select name="type">
			<option value="fiction">Fiction</option>
			<option value="non-fiction">Non-Fiction</option>
		</select>
	</div>
	<div class="row">
		I'm interested in…
		<input type="checkbox" name="option1" value="Print"> Print
		<input type="checkbox" name="option2" value="Ebook"> Ebook
	</div>
	<div class="row">
		My book contains…
		<input type="checkbox" name="option1" value="tables"> Lists or Tables
		<input type="checkbox" name="option2" value="verse"> Verse
		<input type="checkbox" name="option2" value="images"> Images
		<input type="checkbox" name="option2" value="footnotes"> Footnotes
	</div>
	<label class="row" for="message">Your Message:</label>
	<textarea class= "row" name="message" rows="10" cols="30">
	</textarea>
	<input type="hidden" name="_subject" value="New submission!" />
	<input type="text" name="_gotcha" style="display:none" />
	<input type="text" name="_format" value="plain" style="display:none" />
	<input type="submit" value="Send">
</form>