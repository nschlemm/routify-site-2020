<script>
  import { url, meta, context } from "@sveltech/routify";
  import Prism from "svelte-prism";
  import { Tabs, TabsLink, TabsPage } from "@sveltech/bricks";
  const title = $context.component.meta.$name
  meta.title = title;
</script>

<!-- routify:options $index=10 -->
<!-- routify:options $name="Creating an app" -->



<h1 class="c-h1">{title}</h1>
<div class="c-content">
  <p>
    To create a new Routify project, create a new folder, then navigate to it, open your terminal and type
    <code>npx @sveltech/routify init</code>
  </p>
  <p>This will initialize the Routify starter project (see this <a href="https://github.com/sveltech/routify-starter">repo</a>) in the folder.</p>
  <p>Alternatively, download the repository and follow the instructions.</p>
  <p>
      If you wish to add Routify to an existing project, please refer to our
      <a href={$url('../../guide/install')}>install guide</a>.
  </p>
</div>
