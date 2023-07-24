# Warwick in Africa blog website

## History
This website was started in 2023 to showcase my journey (Maks Manowski) in Warwick in Africa.

During my time in WIA, I went to South Africa for 6 weeks (29th July to 10th Sept) and taught mathematics at a high school in the Limpopo region.

This blog showcases my fundraising, training and teaching over the year during the programme. I am very happy and open to people contributing to this website and details are given below on how to do this.

This blog also contains all content I am sharing from my trip, with videos, photos and learning resources being openly available. If you would like to reproduce any of these the details for reproduction are below.

It uses the hugo static site builder and [hugo-theme-cleanwhite](https://themes.gohugo.io/themes/hugo-theme-cleanwhite/) as a template.

## How to contribute

>Note: By posting materials and articles on this website you agree to give redistribution rights and release your materials equivalently to the copyright release below and any future changes.
>These rules have been chosen to allow future WIA students to be able to reproduce all work whilst ensuring work is credited.

These are the following steps I have taken to create pages. I recommend following these for basic users. 
If you would like to post here but are finding this difficult please get in contact with me and I can help!

### 1. Write and design your article.
>During this step, I recommend using something like Google Docs and restricting yourself to the following functions:
> - Headings (Title, subtitle etc)
> - Bolds & Italics (Underlining is **not** supported)
> - Hyperlinks
> - Images & Youtube videos

### 2. Convert your formatted article into markdown.
>   1. First copy and paste all text into [a markdown previewer](https://markdownlivepreview.com/).
>   2. Then, edit the text to include the formatting in your document. There is a preview of styling on the webpage listed, alternatively follow this guide:
> 
>   > #### Headings, Titles and Subtitles
>   > To add a title, add `# ` before the line including the title.
>   >
>   > For a subtitle add `## `. The more `#` you add to the beginning, the smaller the subheading is.
>   > ```markdown
>   > # Title
>   > ## Heading 1
>   > ### Heading 2
>   > ```
>
>   > #### Bold and italic
>   > To make text italic, put `*` encompassing the text.
>   >
>   > To make text bold, put `**` encompassing the text.
>   >
>   > To make text bold and italic, put `***` encompassing the text.
>   >
>   > ```markdown
>   > *italic*
>   > **bold**
>   > ***italic and bold***
>   > ```
> 
>   > #### Hyperlinks
>   > To add a hyperlink, encase the text to link to in square brackets `[]` and follow this by circular brackets `()` containing the URL.
>   >
>   > ```markdown
>   > [Maks' Website](www.manowski.me)
>   > ```
>
>   > #### Images and YouTube videos
>   > To add a single image add the link and caption to: `{{< figure link="/img/your/link/here/name.jpg" caption="your caption here" >}}`.
>   >
>   > To add multiple images please see [Hugo Easy Gallery](https://www.liwen.id.au/heg/#gallery-usage). Surround multiple figures in `{{ <gallery> }}` tags.
>   >
>   > To add an embedded YouTube video, copy the video's id and make a new line: `{{< youtube id >}}`.
>   > ```markdown
>   > {{< figure link="/img/homepage/sydney-harbour.jpg" caption="Sydney Harbour" >}}
>   > 
>   > {{< gallery >}}
>   > {{< figure link="/img/homepage/sydney-harbour.jpg" caption="Sydney Harbour" >}}
>   > {{< figure link="/img/homepage/cc_jeepers.jpg" caption="Capital Chorus" >}}
>   > {{< figure link="/img/arduino/test-setup.jpg" caption="Arduino test setup" >}}
>   > {{< /gallery >}}
>   > 
>   > {{< youtube cllc1ZGlhsQ >}}
>   > ```

### 3. Adding meta data to your markdown file:
> The following is required for the file to be read and be seen on the blog page:
> ```markdown
> ---
> layout: post
> title: "Title"
> subtitle: "Subtitle"
> excerpt: "Excerpt"
> author: "Author"
> date: YYYY-MM-DD
> description: "Description"
> image: "/img/folder/background.jpg"
> published: true
> tags:
> - Tag
>   categories: [ Tech ]
>   URL: "/chosen/url/"
> draft: true
> ---
> 
> > Copy of description
>
> # Here starts your title
> ```
> 
> For each metadata information either fill in the relevant information or delete the line pertaining to the information.
> 
> The minimum metadata required is as follows:
>
> ```markdown
> ---
> layout: post
> title: "Title"
> subtitle: "Subtitle"
> excerpt: "Short, Interesting, Excerpt"
> author: "Prefered Name (& optionally Surname)"
> date: YYYY-MM-DD
> description: "Short description"
> image: "/img/folder/background.jpg"
> ---
> 
> > Copy of description:
>
> # Here starts your title
> ```

### 4. Uploading your files online
> Go on the [GitHub page](https://github.com/MaksManowski/wia-blog). 
> 
> Inside [wia-blog/content/post/](https://github.com/MaksManowski/wia-blog/tree/master/content/post) upload your markup file.
> 
> Inside [wia-blog/static/img](https://github.com/MaksManowski/wia-blog/tree/master/static/img) upload your images. (These should be in the correct folder, make one!)

### 5. Wait!
> Once you have submitted your push requests, someone will review these and then publish your page. They may also edit it the top to make sure it fits the correct format.
> 
> If you would like to be an administrator/mod to be able to review and accept your own or others' publications please get in contact.

## Usage and copyright release
Usage varies depending on who you are and which organisation you work for. Please find below which applies to you*.

### Warwick in Africa Staff
Persons in direct management of the WIA program through the Warwick SU or Warwick University have unrestricted access to these materials for usage as part of Warwick in Africa.

For usage unrelated to Warwick in Africa, please see 'Others'.

### Students who partake or have partaken in Warwick in Africa
Any student who has partaken in the Warwick in Africa programme can use any material here as long as they credit the author and original source.

### Non-profits & Charities for non-commercial use
Any charity or non-profit organisation may use material here for non-commercial usage as long as they both:
1. Credit the Author
2. Credit Warwick in Africa

For commercial use either contact the author or site admin.

### Others
Please contact the site admin or author of the content you wish to use.

*Subject to change. If you lawfully have previously used content you can keep using the previously used content.

## Contact details

Site admin: Maks.Manowski (@) warwick.ac.uk