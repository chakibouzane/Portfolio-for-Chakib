<script lang="ts">
	import { _ } from 'svelte-i18n';
</script>

<section
	id="skills"
	class="flex flex-col justify-center gap-5 pt-32 pb-0 sm:pt-24 sm:pb-7 items-start mx-8 sm:mx-64"
	style="font-family: Arial, Helvetica, sans-serif;"
>
	<h6 class="uppercase text-xl tracking-wide font-bold text-gray-300">
		{$_('skillsSection.title')}
	</h6>
	<div class="w-full flex flex-row flex-wrap justify-start items-start gap-y-8 gap-x-16">
		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.languages')}</h6>
			<ul class="list-disc list-inside">
				<li>JavaScript / TypeScript</li>
				<li>Python</li>
				<li>Java</li>
				<li>R</li>
				<li>SQL</li>
			</ul>
		</div>

		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">AI & ML</h6>
			<ul class="list-disc list-inside">
				<li>TensorFlow</li>
				<li>PyTorch</li>
				<li>Scikit-learn</li>
				<li>Pandas</li>
				<li>NumPy</li>
			</ul>
		</div>
		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.cybersecurity')}</h6>
			<ul class="list-disc list-inside">
				<li>IoT & Network Security</li>
				<li>RPL Protocol & Threat Modeling</li>
				<li>Intrusion & Anomaly Detection</li>
				<li>Cryptography Algorithms</li>
				<li>Blockchain</li>
			</ul>
		</div>
		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.webDev')}</h6>
			<ul class="list-disc list-inside">
				<li>Svelte & SvelteKit</li>
				<li>React</li>
				<li>Node.js & Express.js</li>
				<li>REST APIs & GraphQL</li>
			</ul>
		</div>
		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.databases')}</h6>
			<ul class="list-disc list-inside">
				<li>Supabase</li>
				<li>MongoDB</li>
				<li>PostgreSQL</li>
				<li>Redis</li>
			</ul>
		</div>
		<div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.toolsOther')}</h6>
			<ul class="list-disc list-inside">
				<li>Git & GitHub</li>
				<li>Docker</li>
				<li>Contiki-NG/Cooja & GNS3</li>
				<li>LaTeX</li>
			</ul>
		</div>
		<!-- <div class="flex flex-col gap-3 min-w-40">
			<h6 class="font-semibold text-lg">{$_('skillsSection.itSystems')}</h6>
			<ul class="list-disc list-inside">
				<li>{$_('skillsSection.networking')}</li>
				<li>IoT</li>
				<li>{$_('skillsSection.arduino')}</li>
			</ul>
		</div> -->
	</div>
</section>
