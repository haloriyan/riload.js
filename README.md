# Riload - Javascript Library LazyLoad

Riload is a open-source library for help us to developping a lazyloading method. We just set the URL and DOM then we can lazyloading.

Note : This is plugin for [embo.js](https://github.com/haloriyan/embo "EmboJs"). You must link that before using this.

## Usage
```
<div id='myDom'></div>
<script src='embo.js'></script>
<script src='riload.js'></script>
<script>
let app = new Riload({
	el: '#myDom',
	url: 'https://service.mysite.com/posts'
})
</script>
```