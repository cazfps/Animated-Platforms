# Animated Platforms

An animated ground plane for Blockbench to preview motion (walk cycles, vehicles, etc.) by scrolling a textured plane under your model.

This is especially useful for Minecraft mobs / entity animation, but it works for any animation workflow.

<style>
	.ap-links {
		display: flex;
		gap: 22px;
		justify-content: center;
		flex-wrap: wrap;
		margin: 18px 0 10px;
	}
	.ap-links a {
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 8px;
		text-decoration: none;
		color: var(--color-text);
		min-width: 150px;
		padding: 10px;
		border-radius: 4px;
	}
	.ap-links a:hover {
		background-color: var(--color-selected);
		color: var(--color-light);
	}
	.ap-links i {
		font-size: 32px;
	}
</style>

<div class="ap-links" data-ap-plugin="animated_platforms">
	<a class="open-in-browser" href="https://x.com/cazfps1" title="https://x.com/cazfps1">
		<i class="fa-brands fa-twitter" style="color:#00acee"></i>
		<label>X / Twitter</label>
	</a>
	<a class="open-in-browser" href="https://www.cazfps.com/links" title="https://www.cazfps.com/links">
		<i class="fa-solid fa-globe"></i>
		<label>Website</label>
	</a>
	<a class="open-in-browser" href="https://discord.gg/KDd2rcAPqA" title="https://discord.gg/KDd2rcAPqA">
		<i class="fa-brands fa-discord" style="color:#5865F2"></i>
		<label>Discord Server</label>
	</a>
</div>

## Features
- Scroll speed in blocks/sec (with quick presets)
- Size/placement controls (width/length/height, rotation)
- Optional custom texture + rotate/flip
- Texture library for quick reuse
- Per-animation presets (save / auto-save)

## Notes
- Custom texture rotation is visual only; movement direction stays consistent.
- Presets are stored locally (Blockbench localStorage) and are scoped so different projects/animations don’t overwrite each other.

## Author
Cazfps
