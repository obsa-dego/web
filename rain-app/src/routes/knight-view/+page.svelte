<script>
	// Knight View - Blocked
</script>

<svelte:head>
	<title>Knight View - Blocked</title>
</svelte:head>

<div class="page">
	<div class="header">
		<div class="title">
			<span class="bracket">[</span>
			<span class="title-text">knight view</span>
			<span class="bracket">]</span>
		</div>
	</div>

	<div class="blocked-message">
		<span class="blocked-text">Access Blocked</span>
	</div>

	<div class="back-section">
		<a href="/" class="back-link">
			<span class="back-arrow">&lt;-</span>
			<span class="back-text">back to home</span>
		</a>
	</div>
</div>

<style>
	.page {
		width: 100%;
		min-height: 100vh;
		background: #000;
		color: #fff;
		font-family: 'Courier New', monospace;
		padding: 60px 20px;
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 80px;
	}

	.header {
		text-align: center;
	}

	.title {
		font-size: 28px;
		font-weight: normal;
		letter-spacing: 2px;
	}

	.bracket {
		color: #666;
	}

	.title-text {
		color: #fff;
		margin: 0 8px;
	}

	.blocked-message {
		text-align: center;
		padding: 40px;
		border: 1px solid #333;
		background: #111;
	}

	.blocked-text {
		color: #ff0000;
		font-size: 16px;
		font-weight: bold;
		letter-spacing: 1px;
	}

	.back-section {
		margin-top: auto;
	}

	.back-link {
		display: inline-flex;
		align-items: center;
		gap: 8px;
		color: #666;
		text-decoration: none;
		font-size: 14px;
		letter-spacing: 0.5px;
		border: 1px solid #333;
		padding: 12px 16px;
		background: #000;
	}

	.back-link:hover {
		background: #111;
		border-color: #555;
		color: #fff;
	}

	.back-arrow {
		color: #666;
	}

	.back-text {
		color: inherit;
	}

	@media (max-width: 768px) {
		.page {
			padding: 40px 15px;
			gap: 60px;
		}

		.title {
			font-size: 24px;
		}

		.blocked-text {
			font-size: 14px;
		}
	}
</style>