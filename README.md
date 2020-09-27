# GE Smallworld Magik HTML5 Component API Example 

### Introduction

The HTML5 component is a SWIFT component which can be embedded into any control and used to embed rich HTML5 user interfaces into any Smallworld application.( GE Documentation )

The API is very simple, but also very powerful: there are only three functions exposed in JavaScript and two exposed in Magik.( GE Documentation )


This example illustrates the implementation of a basic button and input using HTML5 technologies. ( GE Documentation )

This repository covers some basic tasks with the HTML5 Component API, Sending commands from HTML to Magik, Broadcasting Messages from magik to HTML, Magik Requesting Data from HTML and communicating Magik and HTML with JSON data.

For more information please refer to the Smallworld online documentation.



![](https://github.com/Aramideh/sw_Magik_Html5_Component/blob/master/screenshot.png)


### Getting Started

* Load the module

*
```
_block 
	my_html5_example.new()
_endblock 
$

```



```
	For debuggin the application please add the below line to environment:
	
	set _JAVA_OPTIONS=-Dmagik.html5.debug=3050
	
	after loading the application you can debug with chrome, go to address localhost:3050 
```	



### Author Notes

 * This modules is tested on Smallworld 5.1.9 (Long support )
	
 * I know that HTML look is messy! but it shows how the API works, that is the important issue here! :)



### Authors
* [**Sadeq Aramideh**](https://github.com/Aramideh)

