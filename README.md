# js-notes
# Learning JS My Notes

SCRIPT TAG

The script tag in javascript can be used inside the HTML file or as an external link


If we have a larger codebase its better to use external link cause the browser will download it and store it as the cache so other pages that references the same script just refer to that cache insted of downloading the script again

Also if we use external script we cant use internal script in same tag ex
<script scr="file.js>
alert(1);                  //This cannot be done 
</script>

instead we can write like this 
<script src="files.js></script>
<script>
    alert(1);
</script>