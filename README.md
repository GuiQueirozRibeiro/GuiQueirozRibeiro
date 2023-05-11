[Enlish](_data/readme_en.md)
[Portugues](_data/readme_en.md)
<!-- HTML code to create a switch button -->
<input type="checkbox" id="switch" />
<label for="switch">Toggle Text</label>

<!-- Markdown content that will be hidden by default -->
<details>
<summary>Original Text</summary>

This is the original text that will be hidden when the switch button is turned on.

</details>

<!-- JavaScript code to toggle the visibility of the Markdown content -->
<script>
  var switchButton = document.getElementById('switch');
  var content = document.querySelector('details');
  
  switchButton.addEventListener('change', function() {
    if (this.checked) {
      content.removeAttribute('open');
    } else {
      content.setAttribute('open', true);
    }
  });
</script>
