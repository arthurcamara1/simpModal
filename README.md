simpModal
=========

**simpModal** is a simple modal jquery plugin based on leanModal by FinelySliced ([See their website](http://leanmodal.finelysliced.com.au/)).

I built **simpModal** because I wanted flexibility. Many of the modal plugins I've seen out there rely on lots of HTML markup, which makes them too complex for simple things. Plus, I wanted to be able to code my CSS separately from the plugin, which certainly makes it a lot more designer-friendly. Finally, I wanted the plugin to add/destroy any necessary HTML tags it may need automatically, so that I wouldn't have unnecessary tags when a modal isn't visible.

---

### Best things about this plugin so far

* Simple
* Flexible width and height
* Independent CSS
* Ajax Support (with very useful options)
* Image Free
* Very light (less than 4Kb)
* Multiple instances on the same page
* Many options
* Very easy to use
* Events (yay!)

### Yet to be improved

* No support for old IE browsers
* No iframe support
* No gallery support

---

## Examples and Usage

It's super simple to open a new modal using simpModal. The following code would do!

	$.simpModal({
		content: "This is super cool!"
	});

And there are many possible settings, which are simple to use as well. This would change the default animation, speed, and add an extra class to the modal:

	$.simpModal({
		content: "This is super cool!",
		transition: "slideUp",
		speed: 200
		extraClass: "myModalClass"	
	});

Advanced settings using Ajax and callback functions are equally simple to implement using simpModal:
	
	$.simpModal({
		ajax: {
			file: 'coolpage.php',
			onSuccess: function() {
					alert('Yay!');
				}
			}
	});

See [this page](http://www.arthurcamara.com/simpmodal) or download simpModal to see more examples and all possible settings.

---
## Download
[On my website](http://www.arthurcamara.com/simpmodal) or on [GitHub](https://github.com/arthurcamara1/simpModal)

---
#### About Me
My name is Arthur Câmara. I’m a web designer and developer from Belo Horizonte, Brazil. [Check out my website](http://www.arthurcamara.com) or [send me an email](mailto:arthurcamara@gmail.com)

