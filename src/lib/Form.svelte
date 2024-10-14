<form class="flow" method="GET">
	<h2>Send us a message</h2>

	<div>
		<label for="first">First Name <span>*</span></label>
		<input
			type="text"
			id="first"
			name="first"
			placeholder="Enter first name..."
			required
		/>
	</div>

	<div>
		<label for="last">Last Name <span>*</span></label>
		<input
			type="text"
			id="last"
			name="last"
			placeholder="Enter last name..."
			required
		/>
	</div>

	<div>
		<label for="email">Email <span>*</span></label>
		<input
			type="email"
			id="email"
			name="email"
			placeholder="Enter email address..."
			required
		/>
	</div>

	<div>
		<label for="tel">Phone <span>*</span></label>
		<input
			type="tel"
			id="tel"
			name="tel"
			placeholder="Enter phone number..."
			required
		/>
	</div>

	<div>
		<label for="message">Message <span>*</span></label>
		<textarea
			name="message"
			id="message"
			rows="10"
			placeholder="Please enter message..."
			required
		></textarea>
	</div>

	<button class="bg-blue white">Send Message</button>
</form>

<style>
	form {
		max-width: 32rem;
	}

	div {
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
		background: var(--gradient-pink);
	}
</style>
