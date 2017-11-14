<template>
  <page-container centered :title="$t('pages.themes.title')">
    <div class="page-container-section">
      <h2 class="md-headline">Theme Engine</h2>

      <p>The concept of themes on Vue Material have four pillars: Dynamic, Multiple, Flexible and Friendly.</p>
      <ul>
        <li>Dynamic: You can apply dynamic themes an change them anytime you want, through an declarative API. Once you set a theme to a specify component, all of it's children will get the same color scheme.</li>
        <li>Multiple: Each component of your page can have a different theme if you want.</li>
        <li>Flexible: You can create light or dark themes. You can also theme only the themes that you're really using, on demand and on build time. </li>
        <li>Friendly: The theme engine will automatically calculate the contrast between the background and the text for you. This means that no color on Vue Material will be hard to read. Score!</li>
      </ul>
      <p>As Vue Material can have dark themes too, the background color of most elements is applied automatically.</p>
      <p>Every component can also work with two color intentions, that will change the background and foreground colors: Primary and Accent. Some components also have a Transparent variant to make your layouts cleaner and easy to place on top of another element. E.g. Tabs inside toolbars.</p>
    </div>

    <div class="page-container-section">
      <h2 class="md-headline">Color Intentions</h2>

      <p>Color in Material Design is inspired by bold hues juxtaposed with muted environments, deep shadows, and bright highlights. The <a href="https://material.google.com/style/color.html#color-color-palette" target="_blank" rel="noopener">Material Design palette</a> can be fully applied here, and you should use the name and the hue number to create themes.</p>
      <p>Vue Material use classes to apply those color intentions: <code>md-primary</code>, <code>md-accent</code>, and <code>md-transparent</code>. The background color is applied automatically by the theme engine.</p>
      <note-block>Although is possible, is not recommended to use in primary and accent the same color.</note-block>
    </div>
  </page-container>
</template>

<script>
  export default {
    name: 'Concepts'
  }
</script>