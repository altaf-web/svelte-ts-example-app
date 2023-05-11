<script lang="ts">
	import Image from "./Image.svelte";
	import Assignments from "./Assignments.svelte";
	import Declarations from "./Declarations.svelte";
	import UpdatingArraysAndObject from "./UpdatingArraysAndObject.svelte";
	import DeclaringProps from "./DeclaringProps.svelte";
	import IfBlock from "./IfBlock.svelte";
	import IfElseBlock from "./IfElseBlock.svelte";
	import ElseIfBlock from "./ElseIfBlock.svelte";
	import EachLoop from "./EachLoop.svelte";
	import KeyedEachBlock from "./KeyedEachBlock.svelte";
	export let name: string;
</script>

<main>
	<KeyedEachBlock />
<!--
	<EachLoop />
	<ElseIfBlock />
	<IfElseBlock />
	<IfBlock />
	<DeclaringProps />
	<UpdatingArraysAndObject />
	<h1>Hello {name}!</h1>
	<p>Iam the Paragraph text</p>
	<Image />
	<Assignments />
	<Declarations />
    -->
</main>

<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>