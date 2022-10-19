## Welcome to my vehicle dashboard project

<!--You can use the [editor on GitHub](https://github.com/Eas94/dash/edit/master/README.md) to maintain and preview the content for your website in Markdown files.-->

### Features
Besides indicating vehicle speed and other common driver information, ambition is to include driver assistance  features like blindspot detection with contextual alerts, lane keeping alert, a simple 2D-view of the road ahead and perhaps even road surface condition estimation, birds-eye-view parking assist and forward collision warning. Sky's the limit.

### Hardware

The project will be equipped with a [Waveshare 7.9" IPS touch display](https://www.waveshare.com/product/raspberry-pi/displays/7.9inch-dsi-lcd.htm) with the resolution 400x1280, for a sleek aspect ratio of 16:5. This will be driven by a Raspberry Pi, hopefully equipped with radar distance sensors and an OBD-II reader. Nvidia Jetson or similar is needed if image analysis is to be implemented.

### Software
Further research is needed here, but Python will be used for drafting code. Trafikverket's [Lastkajen](https://lastkajen.trafikverket.se) will supply geospatial vector data for map features.


<!---
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```



### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Eas94/dash/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
