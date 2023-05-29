<script lang="ts">

	/*
		import SelectBindings from "./SelectBindings.svelte";
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
        import AwaitBlocks from "./AwaitBlocks.svelte";
        import DomEvents from "./DomEvents.svelte";
        import InlineHandler from "./InlineHandler.svelte";
        import EventModifiers from "./EventModifiers.svelte";
        import ComponentEvents from "./ComponentEvents.svelte";
        import EventForwarding from "./EventForwarding.svelte";
        import TextInput from "./TextInput.svelte";
        import NumericInput from "./NumericInput.svelte";
		import CheckboxInput from "./CheckboxInput.svelte";
		import GroupInputs from "./GroupInputs.svelte";
		import TextareaInputs from "./TextareaInputs.svelte";
		import ContentEditableBindings from "./ContentEditableBindings.svelte";
		import OnDestroy from "./OnDestroy.svelte";
		import Box from "./Box.svelte";
    */
import SlotFallbacks from "./SlotFallbacks.svelte";
</script>

<main>
		<SlotFallbacks>
			<h2>Hello!</h2>
			<p>This is a box. It can contain anything.</p>
		</SlotFallbacks>
		<SlotFallbacks />
	<!--
		<Box>
			<h2>Hello!</h2>
			<p>This is a box. It can contain anything.</p>
		</Box>

		<OnDestroy />
		<ContentEditableBindings />
		<SelectBindings />
		<TextareaInputs />
		<GroupInputs />
		<CheckboxInput />
		<NumericInput />
        <TextInput />
        <EventForwarding />
        <ComponentEvents />
        <EventModifiers />
        <InlineHandler />
        <DomEvents />
        <AwaitBlocks />
        <KeyedEachBlock />
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