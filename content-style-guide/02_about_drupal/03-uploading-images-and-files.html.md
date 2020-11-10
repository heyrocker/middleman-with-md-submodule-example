---
title: Uploading Images And Files
layout: article
category: About Drupal
---

## Files
Here are things to keep in mind when adding files.

### Does this need to be a file?
While everyone has access to PDFs, they are hard to use on smaller devices. Many other formats like Word files also don't work well across different devices and software.

* Consider a web form for fillable forms. Contact the Web Team for assistance in creating a web form.
* Consider a "Basic page" for general information. Contact the Web Team if you would like help with events, complex data, or other detailed formatting.

### What kind of file?

* If you anticipate people printing it out or writing on it by hand, use a PDF.
* If you have complex tabular data, use an Excel spreadsheet.
* If you have a presentation to be shared after an event, convert it to a PDF or use a PowerPoint file.

### Upload your file
(See Replacing a File below if you are updating an existing document.)

1.	Go to My Workbench > Upload File. 
2.	Click Choose File and select your file.
3.	Click Open. 
4.	If the file is a PDF, be sure that you have made an accessible PDF, and check the box marked "Reviewed for Accessibility." 
5.	Choose the "Site Section" (optional), type "Alt Text" (for an image), and add a "Description" (required).
6.	Click Save. 

**Note:** It is important to write good descriptions! This makes it possible for you and others to find this file later when you want to use it in the site.

![Screenshot of Drupal's Upload File page](images-and-files--upload-file.png)

### Link to the file
- Edit the page you want to link from.
- Find the text you want to link, or add it yourself.
- Highlight the link text (and file type). Example: Admission Form (PDF) 
- Click on the link button.

![Screenshot of higlighting a piece of text in Drupal](images-and-files--linking-link-button.png)

- Use Search for content to find the file you uploaded. (You may have to scroll to the bottom to see the files).

![Screenshot of higlighting a piece of text in Drupal](images-and-files--linking-search.png)

- Select the correct file and click Save.
- Click Save to save the changes to the page.

####Writing good link text
Describe what people should expect when they click on the link. That means both a clear title of the file and the file type. The file type MUST ALWAYS be included in the link for accessibility reasons.

**Good:** 

Download the [Military Tuition Waiver (PDF)](#).

*[The link includes the form name and the file type is in the link. Optionally include the file size.]*

**Bad:** 

If you might be eligible, please [download the form](#). 

*[There is no form name, and the link doesn't indicate that it's a Word document to be downloaded! A better link would be [Complete the Registration Form (Word)](#)]*

### Removing and Replacing a File
- Go to Manage, then Content,then the Media tab.
- On this screen you can find your file by searching for its name. 
- Once you find your file, look to the column labeled Operations in the same row as your file, and click the arrow next to the word "Edit".
- Choose Delete.
- Conform the delete by clicking delete again.
- Follow the steps above to upload the new file. 

![Screenshot of steps to delete a file in Drupal](images-and-files--delete-file.png)

### New Feature: List of Documents
If you have many files that you are linking, try using the [List of Documents](../04_paragraph_types/09-list-of-documents.html). This list takes care of some of the formatting issues for you, and helps to organize your list with a good header.

For more information about how to add a List of Documents, refer to [Working With Paragraphs](../02_about_drupal/05-working-with-paragraphs.html).

## Images

While editing a page, click the Image button. When doing this, you can use previous images, or upload something new.

![Screenshot of CKEditor Image upload button](images-and-files--upload-button.png)

### Using a previously uploaded image

* Select Choose an existing image to use an image that's been previously uploaded. Search by name, or scroll through the library.
* Check the box next to the image you want. 
* Click Select entities to continue.

![Screenshot of chooseing an existing image in CKEdtor](images-and-files--choose-existing.png)

### Upload an image

* Click Upload new image to add a new file. Images may be no larger than 32 MB. They will automatically be resized when they appear on the page to be no larger than 850 pixels wide, but your original image will be saved as well.
* Enter a name for your image. You can use the file name or something that's more descriptive.
* Browse to upload the image. 
* Fill in Alternative text that will be available when someone can't see the image. This includes, for example, people who are blind and visitors on very slow internet connections. If the image is merely decorative, use "" as the description (more info about this below).
* Optionally include a Site Section.
* Click Save entity to continue.

![Screenshot of uploading a new image in CKEditor](images-and-files--upload-new.png)

### Styling your image
After you have selected an image, you can set its final alt text and style. 

![Screenshot of image embed options for styling](images-and-files--embed-options.png)

#### Alt text
You can either type in new text, or leave it with what was entered on the last screen.

The alternate/alternative text should be an informational equivalent to the image for someone who cannot see it.
You do NOT need to say that it is an image, but if there are words in the image, the alternative text should be an exact copy of those words. If there are too many words to include in alternative text, then you should replace the image with a different type of content. Contact the Web Team for design assistance if necessary.

You can also set an image as decorative by typing "" in the alternative text field. A decorative image is one that you could leave out entirely and someone would still understand the full contents of the webpage. If you are using a Caption, you may set the image as decorative.

#### Image alignment
None or Center behave the same and will display the image on its own line.

Right and Left both float the image to the right of the text. We understand this is weird, but this is how it currently works.😄

#### Caption
You can easily put an image and caption together in a box with a background color. Adding text to the Caption field will automatically add that for you. If you do not add a caption, the image will be displayed with no background color.

If you are using a Caption, and the caption contains the same information as the image, you may set the image as decorative by typing "" in the Alternative text field.

Here is an example of how a right or left-aligned image with a caption will look on the site. 

![Screenshot of a right-aligned image on the Evergreen website](images-and-files--right-align.png)

Here is an example of how a centered image with a caption will look on the site. 

![Screenshot of a right-aligned image on the Evergreen website](images-and-files--center-align.png)
