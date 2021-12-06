---
layout: default
title: NewEx1
parent: Index
nav_order: 2
---

# Add a Text Alternative to Images for Visually Impaired Accessibility
## Exercise

Like many others, Peter suffers from visual impairment and relies on screen readers to convert all web content to an audio interface. He will not perceive information if it's only presented visually, since it would equal to the screen being turned off for an individual, who does not suffer from visual impairments. Figure 1 attempts to illustrate this. 

| ![Figure 1: A visual impaired individual will not be able to process visual information](https://media.discordapp.net/attachments/363271799594811394/913012062492430366/PCCompare.jpg?width=1070&height=319) | 
|:--:| 
| *Figure 1*|

Specific, for images, screen readers can access the `alt` attribute and read its contents to deliver key information to Peter. This means that the `alt` text should be relevant to whats on the picture otherwise Peter has no idea what is on the image. Because of this, the `alt` text should NOT be a list of keywords, but instead a short sentence describing what is on the image. In HTML the `alt` attribute is added like this: 

```html
<img src="myImage.jpeg" alt="alternative text">
```

- Help Peter accessing the image by adding an `alt` attribute.

## Examples

|![Figure 2: _Close-up of a bear's face_](https://d1mdce1aauxocd.cloudfront.net/_imager/files/Example-Images/Landscape/36/bear_13bf39d392361437fc6b4a44b906c932.jpg) |
|:--:| 
| *Figure 2*|

Here are some examples of good and bad `alt` text for the image on Figure 2:

**Bad:**    
```html
<img src="bear.jpeg" alt="We're zoomed-in on the face of a brown bear – sometimes known as a grizzly – gazing majestically into the middle distance. Perhaps she's hungry, or has spotted a threat?">
```
```html
<img src="bear.jpeg" alt="bear, brown bear, grizzly, grizzly bear, mammal, carnivore">
```
**Okay:**    
```html
<img src="bear.jpeg" alt="Brown bear">
```
**Good:**    
```html
<img src="bear.jpeg" alt="Close-up of a bear's face">
```


*More examples can be found [here][1]*  

[1]: https://supercooldesign.co.uk/blog/how-to-write-good-alt-text
