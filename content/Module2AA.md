---
layout: default
title: Module 2
nav_order: 7
---

<p style="margin-bottom: 20px"></p>

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
 - TOC
{:toc}
</details>

# Module 2: How to use AudiAnnotate?

Now that we know what online annotation is, how it is possible to annotate audiovisual materials and how AudiAnnotate can be helpful in doing that, let us explore how to use this digital tool.

By the end of this module, you will be able to:

*  Follow the necessary steps to use AudiAnnotate
*  Create a new project
*  Obtain a shareable GitHub repository containing your annotated version of the audivisual material

## Using AudiAnnotate

Please create a [GitHub](https://github.com/){:target="_blank"} account if you don’t already have one.
{: .prereq}

To use AudiAnnotate, follow these steps:

### Log in on AudiAnnotate and Create a New Project

1. Go to the [AudiAnnotate application](http://audiannotate.brumfieldlabs.com){:target="_blank"}
2. On the top right corner, click on **Sign in** to access the application with your GitHub account
   
![image](https://github.com/mylovedsystem/IntrotoIIIF/assets/140271862/a0f2104c-be8e-4d5c-a855-a9e5d777c253)

3. GitHub will ask you to authorize AudiAnnotate to use your GitHub account. Click on the **Authorize** green-coloured button and then enter your password.
4. You should land on a page with the following icon as the only content. Click on **New Project**

![image](https://github.com/mylovedsystem/IntrotoIIIF/assets/140271862/85bde92d-2c19-46d5-9f76-3b503ffe6bd4)

5. You will be asked to create a title, a project description and a project slug (the project's GitHub repository name). Fill out the boxed and click on **Create Project**

This project will be hosted in your personal GitHub as a repository so you have the full access.

### Create an Audiovisual Item

1. In the project you just created, click on **Create Item Manifest**
2. AudiAnnotate will ask you to add metadata associated with your project’s audio or video. First, name this item in the `Label` field. The label refers to the title you want to give to the audiovisual material.
3. Then, paste the link of your <b>video or audio file</b> in the `​​Audio File URL` field <br>

If you have a file on your computer, but not a URL, upload it to a file-hosting site like [**The Internet Archive**](https://archive.org/){:target="_blank"} or [**Box**](https://box.com/){:target="_blank"}  in order to generate a URL for it.<br>
AudiAnnotate supports direct links to:<br>
**Audio**: HTML: MP3, WAV, and OGG.<br>
**Video**: MP4, WebM, and Ogg<br>
Make sure these files do not contain sensitive data or information that you do not want to publicize. Open resources like [**The Internet Archive’s Audio Archive**](https://archive.org/details/audio){:target="_blank"} are recommended.
{: .note} 
<br>4. Add the duration of the audio or video material. Duration can be input in minutes:seconds ( e.g: 25:50 ) or hours:minutes:seconds ( e.g: 1:10:24 )
<br>5. Optionally, you may include the Item Homepage URL, the Provider Name and the Provider URL. This information comes from the website you copy the vide URL from.<br>6. Click on **Save**. This will save the metadata you added to this item in the IIIF manifest.

### Update an Annotation File

Now that you created an Audiovisual item on AudiAnnotate, you can start annotating it at your wish. To do so, you will need to create an annotation file by following the next steps:

1. Go to this Google Sheets [template](https://docs.google.com/spreadsheets/d/1KdGD0iGzwT4PL8k93ysexStsM-vM_BKTWhvDXJxQ8Pk/copy){:target="_blank"} and make a copy of it in your own drive by clicking on **Make a copy**
2. The template has 5 columns. Fill them out by taking into account the following criteria:

* *Column A*: type the annotation’s start time (in total seconds or HR:MIN:SEC format)
* *Column B*: type the annotation’s end time (in total seconds or HR:MIN:SEC format)
  
Column A and Column B may be the same point in time or different points in time for a range
{: .note}

* *Column C*: type your annotation (e.g., transcript, description, speaker name)
* *Column D*: include any layers or categories used to describe annotation type (e.g., date, speaker, genre, environment, etc.)
* *Column E*: This column is optional. It is reserved for the index, which is an "end-of-book" list in the project that allows you to pull different annotations across recordings together on one page in connection with different categories. The index is a separate page, and it will appear in the drop-down menu at the bottom. Capitalization should be normalized.

![image](https://github.com/mylovedsystem/IntrotoIIIF/assets/140271862/d61fb56d-3c83-4990-9cb4-f54678015822)
*Example of the annotation template file with filled out information. Source:* [hipstas.github.io](https://hipstas.github.io/documentation/creating-annotations)

3. Once you fill out the information, download the spreadsheet in TSV, CSV, or XLSX formats
4. Go back to the AudiAnnotate's page of the project you created. Under `Add Annotation File`, select the annotation file you just created.
5. Click on `Add` in the same section. AudiAnnotate will now ask you to configure your file so the application knows how to read each column.
   * Use the drop-downs to select the requested information: `start time`, `end time`, `annotation` and `label`
6. Click on `Process`


### Final Presentation

The project will be showcased on a webpage, which can be accessed from the project homepage: *The GitHub Pages site for ______ is* 

The webpage will feature subpages with audiovisual content or explanatory text which can be sharable and easily accessible.


![image](https://github.com/mylovedsystem/IntrotoIIIF/assets/140271862/ba8c2213-645b-4ea6-8498-ce90d80153a0)
*Example of a AudiAnnotate-created project webpage showing an audio material and related annotations. Source: [Library of Congress Blogs](https://blogs.loc.gov/thesignal/2022/08/collaborations-with-embedded-audio-metadata-reusing-cue-chunk-data-for-iiif-web-annotations/)






---


