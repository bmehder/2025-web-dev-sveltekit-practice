<form method="GET">
	<div class="flow">
		<h2>Send us a message</h2>

		<div class="input-group">
			<label for="first">First Name <span>*</span></label>
			<input
				type="text"
				id="first"
				name="first"
				placeholder="Enter first name..."
				required
			/>
		</div>

		<div class="input-group">
			<label for="last">Last Name <span>*</span></label>
			<input
				type="text"
				id="last"
				name="last"
				placeholder="Enter last name..."
				required
			/>
		</div>

		<div class="input-group">
			<label for="email">Email <span>*</span></label>
			<input
				type="email"
				id="email"
				name="email"
				placeholder="Enter email address..."
				required
			/>
		</div>

		<div class="input-group">
			<label for="tel">Phone (Optional)</label>
			<input type="tel" id="tel" name="tel" placeholder="Enter phone number..." />
		</div>

		<div class="input-group">
			<label for="message">Message <span>*</span></label>
			<textarea
				id="message"
				name="message"
				placeholder="Please enter message..."
				rows="10"
				required
			></textarea>
		</div>

		<button type="submit" class="bg-blue white">Send Message</button>
	</div>
</form>

<style>
	form {
		max-width: 32rem;
	}

	.input-group {
		display: grid;
		gap: 0.25rem;
	}

	label {
		font-weight: bold;
	}

	span {
		color: var(--pink);
	}

	input,
	textarea {
		padding: 0.75rem;
		font: inherit;
	}

	button:hover {
		background-image: var(--gradient-pink);
	}
</style>
