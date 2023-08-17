---
layout: default
title: Module 1
nav_order: 2
---
# Module 1: What is IIIF?


At this point, you must be wondering **what IIIF is** and what its different feautures are. **Module 1** will walk you through the basics of the IIIF digital tool!


By the end of this module, you will be able to:

1. Explain the key purpose of IIIF
2. Understand the IIIF Manifest
3. Recognize the four APIs of IIIF



**Activity: Reflection** <br> Take a few moments to consider the digital tools you have used in the past to look up artworks. What did you like about those tools? What were their limitations? How could they have been improved? 
{: .note}



## The Key Purpose of IIIF

In addition to being **a digital tool**, it is helpful to think of the IIIF as **a community**.

Museums, educational archives, and libraries are taking part in this community, sharing their visual aids within one tool. IIIF calls this community the _**IIIF Consortium (IIIF-C)**_ 



<p style="margin-top:20px;margin-bottom:20px">
<img src="figures/IIIFConsortium.jpg" width="600" style="margin-left:30px"/>
</p>
*Some of the members of the IIIF Consortium. If you want to take a look at the full list of the consortium members, [click here](https://iiif.io/community/consortium/members/).*

<br>

Stemming from the Consortium members, the IIIF allows its users to **view images of artworks**, while also conducting various actions with/to the image. 

These capabilities include **enhanced zoom**, **color manipulation**, and **positioning images** next to one another for comparison purposes. In the compare-and-contrast function, the image quality remains unaltered. IIIF also allows the user to **annotate the image**. 


It is helpful to think of IIIF as a *set of standards* for sharing, viewing, comparing and manipulating images. 
{: .note}


## The IIIF Manifest


The IIIF functions as a repository of images (a virtual place where all the images are stored).
 
To achieve this function, IIIF relies on the **the Manifest**. 

The Manifest is the “package” which contains links to the resources that make up the image item. The Manifest takes the form of **a URL** that leads to an online document (in the format of JSON). Ultimately, the IIIF Manifest is the viewing object, itself. It is the object that is viewable through certain digital tools. 

**Definition of URL** <br> 
Uniform Resource Locator. We can think of URLs as the website address that we enter into the search bar. For example: https://ubc-library-rc.github.io
{: .note}

For the purposes of this module, it is important to understand that **the JSON can be read and displayed by IIIF**. 
 
### IIIF Manifest Viewers 

There are at least a dozen tools to view the IIIF Manifest that perform different tasks and have different users. Some of the most-widely known and used viewers are:

* Mirador
* Universal Viewer (UV)
* Tify
* IIIF Curation Viewer 
* Diva.js. 


In a later part of this module, we will be engaging with Mirador, probably the most-well known IIIF viewer. 


## The Four APIs of IIIF

The IIIF has four main [**APIs**][another-identifier] :

The IIIF has four main [**APIs**][id1] :

The IIIF has four main [**APIs**](## "your hover text") :


### Abbreviation
The HTML specification
is maintained by the W3C.
*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium


[id1]: ## "Application Programming Interface, we can think of APIs as software that transmits information between a user and a website/app"




<!-- Identifiers, in alphabetical order -->

[another-identifier]: https://www.altexsoft.com/blog/engineering/what-is-api-definition-types-specifications-documentation/
"Application Programming Interface, we can think of APIs as software that transmits information between a user and a website/app"




1. The image: comprised of pixels
2. Presentation: how the image is presented to the viewer, it will be presented in a format that is highly viewable (in other words, a reasonable size, not difficult to see)
3. Authentication: the IIIF has certain restrictions in place to ensure there is a standard underlying the image presentation; this permits a standard of trust for users (in other words, the image you are seeing is an accurate representation of the artwork; this is particularly useful for art students as they may encounter images online that have been doctored or photoshopped, leaving students uncertain of the accuracy of the image)
4)    Search: there are search functions on the image, for instance those permitting the user to search the annotations of the images and images involving text)
 
In summary, the IIIF is a digital tool that allows users to view and manipulate images, with an added layer of authenticity (trust). 

