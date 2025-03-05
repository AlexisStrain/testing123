This is the lab website for the Kato Lab. Hosted by HugoBlox.  

Notes added by Alexis Strain:
## How to edit website:
- Go to: https://github.com/AlexisStrain/testing123/tree/main/content
- The first file : https://github.com/AlexisStrain/testing123/blob/main/content/_index.md is the home page information
- To edit lab member information go to https://github.com/AlexisStrain/testing123/tree/main/content/authors
  - the admin folder is the PI's page: https://github.com/AlexisStrain/testing123/tree/main/content/authors/admin
  - Each person has their own folder
  - Each folder contains an image called avatar.jpeg. this name must not be changed
  - to add a new person, copy and paste an existing user folder, and then change the information in the new folder
  - When adding new person they can be placed in one of the following user_groups:
    - Grad Students Researchers
    - Undergraduate Researchers
    - Alumni
- To edit the research information go to https://github.com/AlexisStrain/testing123/blob/main/content/research/reasearch.md 
- After editing, click commit changes.
- a menu will popup and require you to type in a message stating what is being updated
- The changes will then automatically be added to the website
- To confirm changes to website URL: "https://alexisstrain.github.io/testing123/"
- If you do not see changes go to: https://github.com/AlexisStrain/testing123/actions. This is part of the site that manages the website uploads. 
  - If you see a red x that means the edits had an error. Click x-> build to see what error was
  - If you see a orange circle the uploads are still being processed
    


## To add photos:
- If you want to add a photo to any page you must first upload you photo to this folder: https://github.com/AlexisStrain/testing123/tree/main/images
- to add image to a page type: ![alternative image text](/images/image.jpeg) where image.jpeg is the name of the image you want

## How to add citations:
- In the folder https://github.com/AlexisStrain/testing123/tree/main, upload a file named publication.bib
- This will contain citations in this format separated by  lines, not commas @article{Strain_2024, author = {Strain, Alexis and Kratzberg, Nathan and Vu, Dan and Miller, Emmaline and Wakabayashi, Ken-ichi and Melvin, Adam and Kato, Naohiro}, doi = {10.1101/2024.10.14.618206}, month = {October}, publisher = {Cold Spring Harbor Laboratory}, title = {Membrane-bound Guanylyl Cyclase COP5/HKR1 changes ciliary beat pattern and biases cell steering during chemotaxis in Chlamydomonas reinhardtii}, url = {http://dx.doi.org/10.1101/2024.10.14.618206}, year = {2024} }
- Publications will be processed and a pull request will be generated here: https://github.com/AlexisStrain/testing123/pulls
- Approve pull request
- Go to: https://github.com/AlexisStrain/testing123/tree/main/content/publication
- Check that all publications have been added. Each publication has it's own folder and can be manually edited now. 




#extra information
 
# [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group)

[![Screenshot](preview.png)](https://hugoblox.com/hugo-themes/)

The **Research Group Template** empowers your research group to easily create a beautiful website with a stunning homepage, news, academic publications, events, team profiles, and a contact form.

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://hugoblox.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/GetResearchDev?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 60 seconds, or [view the showcase](https://hugoblox.com/creators/).

The integrated [**Wowchemy**](https://hugoblox.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://hugoblox.com/hugo-themes/)
- 📚 [View the **documentation**](https://docs.hugoblox.com/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/GetRD/academic-file-converter)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/HugoBlox/hugo-blox-builder/blob/main/CONTRIBUTING.md) or [suggest improvements](https://github.com/HugoBlox/hugo-blox-builder/issues)
- ⬆️ **Updating?** View the [Update Guide](https://docs.hugoblox.com/hugo-tutorials/update/) and [Release Notes](https://github.com/HugoBlox/hugo-blox-builder/releases)

## We ask you, humbly, to support this open source movement

Today we ask you to defend the open source independence of the Wowchemy website builder and themes 🐧

We're an open source movement that depends on your support to stay online and thriving, but 99.9% of our creators don't give; they simply look the other way.

### [❤️ Click here to become a GitHub Sponsor, unlocking awesome perks such as _exclusive academic templates and widgets_](https://github.com/sponsors/gcushen)

## Demo credits

Please replace the demo images with your own.

- [Female scientist](https://unsplash.com/photos/uVnRa6mOLOM)
- [2 Coders](https://unsplash.com/photos/kwzWjTnDPLk)
- [Cafe](https://unsplash.com/photos/RnDGGnMEOao)
- Blog posts
  - https://unsplash.com/photos/AndE50aaHn4
  - https://unsplash.com/photos/OYzbqk2y26c
- Avatars
  - https://unsplash.com/photos/5yENNRbbat4
  - https://unsplash.com/photos/WNoLnJo7tS8
