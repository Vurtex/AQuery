Welcome to the androidquery GitHub home.

Add it in your root build.gradle at the end of repositories:
``` java
   allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Step 2. Add the dependency	
``` java
   dependencies {
	        compile 'com.github.Vurtex:Android_Query:1.0'
	}
```

Click [here](http://code.google.com/p/android-query/wiki/AsyncAPI) for wiki at GoogleCode
or visit:
http://code.google.com/p/android-query/wiki/AsyncAPI

<<<<<<< HEAD
<div class="text_info">
   		<p>The popularity of jQuery comes down to one simple fact; it significantly reduces the amount of code needed to perform asynchronous tasks and manipulate the DOM. The new project AQuery seeks to do the same thing for Android developers working. To show you what <a href="http://code.google.com/p/android-query/">Android Query</a> can do for UI development, we cite a sample from their project page.</p>
<p><b>Before</b></p>
<p><img alt="" _href="img://Before.png" _p="true" src="/img/Before.png"></p>
<p><b>After</b></p>
<p><img alt="" _href="img://After.png" _p="true" src="/img/After.png"></p>
<p>Android Query simplifies attaching event handlers. Rather than building out an interface or anonymous class, one simply needs to ensure they don’t misspell the event handler’s method name.</p>
<pre>aq.id(R.id.button).clicked(this, "buttonClicked");</pre>
<p>Fragmentation due to differences in screen size and API versions can make getting the most out of a device difficult. Android Query some of these issues by providing its own wrappers around the API. For example, the function “aq.hardwareAccelerated11();” will detect whether or not the device supports API 11 and enable hardware acceleration if appropriate.</p>
<p>When working with different screens sizes, one often starts with a tablet and then removes and reorganizes controls until it fits on a phone. Normally this means you have to inspect the visual tree to see which controls were actually created from the axml file before you attempt to manipulate them in the code behind.</p>
<p>Android Query lets you side-step all the checks by conditionally chaining methods. Consider this snippet:</p>
<pre>aq.id(R.id.address).text(name).background(R.color.red).textColor(R.color.black).enabled(true).visible().clicked(this, "addressClicked");</pre>
<p>If the control address doesn’t exist, all of the setters and event handlers that follow simply become no-ops. While this can make debugging somewhat more difficult, it can dramatically reduce the number of lines needed in your onCreate method.</p>
<p>AQuery also makes invoking asynchronous HTTP requests very easy. It includes support for simple and multi-part POST operations and can accept data in binary, JSON, HTML, and XML formats. Separate support is included for images, where a single line can be used to download an image, cache it, and load the image into control.</p>

Click here to help out:
=======
>>>>>>> 7434e46bbf78506fa8f91518058cb26ed47597b8
<a href='https://pledgie.com/campaigns/22663'><img alt='Click here to lend your support to: AndroidQuery and make a donation at pledgie.com !' src='https://pledgie.com/campaigns/22663.png?skin_name=chrome' border='0' ></a>
