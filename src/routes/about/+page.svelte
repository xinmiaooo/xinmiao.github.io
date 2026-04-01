<script lang="ts">
	import favicon from '$lib/assets/favicon.png';
</script>

<div class="container mx-auto flex flex-col items-center gap-6 px-4 py-16">
	<img src={favicon} alt="Profile" class="h-40 w-40 rounded-full" />
	<div>
		<h1 class="mb-4 text-3xl font-bold">Xinmiao Qu</h1>
		<div class="flex flex-col justify-center gap-3 sm:flex-row">
			<a
				href="https://github.com/xinmiaooo"
				target="_blank"
				rel="noopener noreferrer"
				class="inline-flex items-center gap-2 text-lg text-muted-foreground transition-colors hover:text-foreground"
			>
				GitHub
			</a>
			<span class="inline-flex items-center gap-2 text-lg text-muted-foreground transition-colors">
				/
			</span>

			<a
				href="https://qiita.com/xinmiao1995"
				target="_blank"
				rel="noopener noreferrer"
				class="inline-flex items-center gap-2 text-lg text-muted-foreground transition-colors hover:text-foreground"
			>
				Qiita
			</a>
		</div>
	</div>
</div>
