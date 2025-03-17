# CART210 New media glossary
This is the repository for the collaborative glossary of the New Media Theory(ies), Art, and Practice class.

>[!IMPORTANT]
> ## [Check the glossary here](./glossary.md)

The glossary is constantly improved by the CART210 community throughout the term, with three sprint deadlines.






Each student must:

- choose three terms from the provided list of new media keywords
- conduct research to understand each term's relevance in the context of new media. Explore its historical origins, technological significance, and its influence on contemporary digital culture and society.
- write precise definitions for the chosen terms, addressing the following points in your analysis: why is the term significant in new media? how does it relate to current technologies or media practices? what are paradigmatic examples that illustrate the term or technology? identify the person or group that coined, designed, or popularized the term or technology, if applicable.
- use the Chicago Author-Year citation style strictly for all sources. Each term should reference a minimum of three sources, from which at least two must be academic sources (e.g., books, journal articles, or conference papers).
Include a properly formatted bibliographic entry at the end of your entry. Follow the instructions on how to create references using Markdown.
- link your definitions to other terms in the glossary using internal references.
- provide external references, such as hyperlinks to credible sources or relevant examples, in HTTP/HTTPS format

## Adding new terms

Add your new media terms as individual markdown files <mark>inside the `keywords` folder</mark> of this repository

If using the GitHub UI, contributors can create new files as shown in the following images

1. Create a fork of the original repository in your account

![Fork the repo](images/PR-01.png)

2. You can maintain or change the name of the repo. Press “Create Fork”. This will create a fork of the class' repository in your own space on GitHub.

![Fork the repo](images/PR-02.png)

After forking the repository, you will see that you have a forked version. In the image, see that the the user `CART-ACT` has a repository `CART210-glossary` forked from our main repository hosted by the user `concordia-dcart`

![Fork the repo](images/PR-03.png)

3. Now, in your account, you can create and upload files. Press `Add file` and then choose `Create new file`

![Fork the repo](images/PR-04.png)



Name your file markdown file. Markdown files have the file extension `.md`. If your keyword has more then one word (e.g., “surveillance capitalism”) do not use spaces, use a hyphen instead (i.e., `surveillance-capitalism.md`)

Note: Use lowercase for the filename of your entries, unless it is an acronym (i.e., `UNIX.md` or `GNU.md`)

![Fork the repo](images/PR-05.png)

1. Add the content for your entry using [strict Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Note that the title of the entry should be in `heading 2` followed by a space, that is `## Surveillance capitalism`. Write the rest in plain markdown.

    Citations must be added in the same markdown file. Note that, in markdown, the citations are written as `[^thisisacitation]` in the text, and as `[^thisisacitation]: Author A. Year. Title.` in the references section. 


![Fork the repo](images/PR-06.png)

You can also preview how your entry looks like in HTML by pressing `Preview`

![Fork the repo](images/PR-07.png)




5. When you are happy with your contribution you will commit your changes to your repository. When committing your changes, add a meaningful message (e.g., ”Fix: Typo in the description.”, ”Add: New definition from Steyerl, H. (2016).”)

    You can choose to commit to your `main` branch or to create a `new branch`. For simplicity, we will commit to the `main` branch. Press `Commit changes`

![Fork the repo](images/PR-08.png)

>[!NOTE]
> To commit changes, each contributor will create a pull request using the [GitHub](../main/glossary.md#GitHub) web-based interface. Contributors who know how to interact with [GitHub](../main/glossary.md#GitHub) using other environments (e.g., CLI or IDE), can also use those.

After commiting your changes, you will see in the root of your folder on Github that your fork is a few commits ahead the main repository (since you have changes that have not yet been merged). It may happen that your fork is a few commits behind (because other people may have merged their changes)

![Fork the repo](images/PR-09.png)

6. Now, you will create a Pull request so that your contributions are considered to be merged. For this, you will press “Contribute” and then “Open pull request”

![Fork the repo](images/PR-10.png)

Add a meaningful title and description. The more (meaningful) information, the merrier. Then, press “Create pull request”.

![Fork the repo](images/PR-11.png)

If everything wents fine, you will see your Pull request in “Open” state in the main repository. In the image, see that `CART-ACT` wants to merge 1 commit into the main repository from their repository.

![Fork the repo](images/PR-12.png)

The admin of the main repository will review the changes and will approve the addition, or request changes. The following image, shows the screen of the admin user (not yours)

![Fork the repo](images/PR-13.png)

After your additions are reviewed, and if approved, you will receive a “Merged” confirmation.

![Fork the repo](images/PR-14.png)


## Adding images

To add images, you follow the same workflow that with text. That is, you fork the main repo to your account and then you upload your image into the `images` folder in the repository.

Note:  Only images added to the `images` folder will be accepted.

![Add data](images/04-upload-files.png)

>[!IMPORTANT]
> To commit your changes, you will follow the same process as with text entry. each contributor will create a pull request using the [GitHub](../main/glossary.md#GitHub) web-based interface. Contributors who know how to interact with [GitHub](../main/glossary.md#GitHub) using other environments (e.g., CLI or IDE), can also use those.

When committing your changes, add a meaningful message (e.g., ”Add: Visual collage for virtuality.”



## Rendering your image in the glossary

So far, you have just uploaded your image to the repository. To be displayed, the image has to be linked from your keyword file.

For example, if I want to display the image I made for the keyword `virtual-environment`, I will add the following line to the file `virtual-environment.md` located inside the `keywords` folder:

```![Virtual environment](images/virtualenvironment-vigliensoni.png)```

> [!NOTE]  
> Please note that the relative link above does not indicate the previous folder (as in `../images`). This is correct. GitHub considers the root folder of the repository by default. You may not see the file in your keyword file, but it will render fine in the glossary file.


That link will display this image:

![Virtual environment](images/virtualenvironment-vigliensoni.png)
Background image taken from [^reschke07wallpaper]

[^reschke07wallpaper]: Reschke, Michael. 2007. “800x600 Wallpaper Blue Sky.png.” Wikimedia Commons. December 27. https://commons.wikimedia.org/wiki/File:800x600_Wallpaper_Blue_Sky.png.


## Creating connections to other entries in the repository

To create links to other entries you have to create a hyperlink using the Markdown format. Use relative linking for this. 

For example, if you want to create links for the entries `Github`, `Wiki`, and `Affordance`, you add the following Markdown syntax:

```
[GitHub](../main/glossary.md#GitHub), [Wiki](../main/glossary.md#wiki), [Affordance](../main/glossary.md#affordance)
```

That code will be rendered as:

[GitHub](../main/glossary.md#GitHub), [Wiki](../main/glossary.md#wiki), [Affordance](../main/glossary.md#affordance)


## License

TBD
