<script lang="ts">
  import { Accordion, AccordionItem } from "flowbite-svelte";

</script>

<h1>Heading 1</h1>
<Accordion>
<AccordionItem id="1">
  <h2 slot="header">My Header 1</h2>
  <div  >
    <p class="mb-2 text-gray-500 dark:text-gray-400">
      Lorem ipsum dolor sit amet ...
    </p>
    ...
  </div>
</AccordionItem>
<AccordionItem id="2">
  <h2 slot="header">My Header 2</h2>
  <div  >
    <p class="mb-2 text-gray-500 dark:text-gray-400">
      Lorem ipsum dolor sit amet ...
    </p>
    ...
  </div>
</AccordionItem>
</Accordion>