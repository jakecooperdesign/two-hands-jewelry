---
title: Contact
layout: default
permalink: contact/
description: >
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nostrum harum nobis at nulla doloribus culpa autem esse iste cupiditate error!
---

<section class="form has-margin-bottom-large">
	<div class="columns">
		<div class="column is-8 is-offset-2">
			<form action="">
				<div class="columns form-group">
					<div class="column">
						<label for="name">Name</label>
						<input type="text" name="name" id="name" placeholder="Jane Doe">
					</div>
					<div class="column form-group">
						<label for="input-email">Email</label>
						<input type="email" name="email" id="email" placeholder="jane.doe@gmail.com">
					</div>
				</div>
				<div class="form-group">
					<label class="is-block" for="interest">Interest</label>
					<div class="inset-small has-border">
						<label class="checkbox" for="interest-branding">
							<input type="checkbox" name="interest[]" id="interest-branding" value="branding">
							Branding
						</label>
						<label class="checkbox" for="interest-graphics">
							<input type="checkbox" name="interest[]" id="interest-graphics" value="graphics">
							Graphics
						</label>
						<label class="checkbox" for="interest-web">
							<input type="checkbox" name="interest[]" id="interest-web" value="web">
							Web Design &amp; Development
						</label>
					</div>
				</div>
				<div class="form-group">
					<label for="message">Message</label>
					<textarea name="message" id="message" cols="30" rows="10"></textarea>
				</div>
				<div class="form-group">
					<input type="submit" value="Send">
				</div>
			</form>
		</div>
	</div>
</section>