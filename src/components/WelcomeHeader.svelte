<script lang="ts">
	import RelayText from "./RelayText.svelte";
</script>

<RelayText size={160} />
<p class="subtitle">Командная база знаний — реальное время в Obsidian</p>
<p class="description">
	Расшаривайте папки, редактируйте вместе живыми курсорами, держите всё на
	своём сервере.
</p>

<style>
	.subtitle {
		color: var(--text-muted);
		font-size: 1.25rem;
		margin: 0;
	}
	.description {
		color: var(--text-muted);
		font-size: 1rem;
		max-width: 480px;
		margin: 0;
	}
</style>
