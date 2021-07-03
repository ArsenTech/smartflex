<img alt="logo" src="https://avatars.githubusercontent.com/u/77837204?s=200&v=4">

# Smart Flex
![GitHub](https://img.shields.io/github/license/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub Org's stars](https://img.shields.io/github/stars/Smart-Flex-Framework?color=22b455&label=Smart%20FLex%20Stars&style=for-the-badge)
![GitHub all releases](https://img.shields.io/github/downloads/Smart-Flex-Framework/smartflex/total?style=for-the-badge)
![GitHub package.json dynamic](https://img.shields.io/github/package-json/keywords/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/Smart-Flex-Framework/smartflex?style=for-the-badge)
![Website](https://img.shields.io/website?down_color=dc3545&down_message=Offline&label=SmartFlex%27s%20Website&style=for-the-badge&up_color=22b455&up_message=Online&url=https%3A%2F%2Fsmart-flex-framework.github.io%2F)

CSS only Flex and Flexbox working Framework. <br>
SmartFlex is a CSS Library using Flex and Flexbox. <br>
by [ArsenTech](https://arsentech.github.io)

## Table of Contents
- [Status](#status)
- [Setup](#setup)
- [Includes](#includes)
- [Documentation](#documentation)
- [Issues](#issues)
- [Creators](#creators)

## Status
![GitHub issues](https://img.shields.io/github/issues/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub milestones](https://img.shields.io/github/milestones/all/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/Smart-Flex-Framework/smartflex?style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/Smart-Flex-Framework/smartflex?style=for-the-badge)
![Lines of code](https://img.shields.io/tokei/lines/github/Smart-Flex-Framework/smartflex?style=for-the-badge)

## Setup
You Can Setup (Download and / or Install) by using one of these methods:
- [Download Latest Release](https://github.com/Smart-Flex-Framework/smartflex/releases/)
- Copy CDN 
```
CSS:
https://raw.githubusercontent.com/Smart-Flex-Framework/smartflex/main/dist/css/smartflex.min.css
https://raw.githubusercontent.com/Smart-Flex-Framework/smartflex/main/dist/css/smartflex.css

SCSS:
https://raw.githubusercontent.com/Smart-Flex-Framework/smartflex/main/dist/scss/smartflex.min.scss
https://raw.githubusercontent.com/Smart-Flex-Framework/smartflex/main/dist/scss/smartflex.scss
```
- Clone github Repo (Git Bash) `git clone https://github.com/Smart-Flex-Framework/smartflex.git`

## Includes
```text
smartflex/
├── css/
│   ├── smartflex.css
│   └── smartflex.min.css
└── scss/
    ├── smartflex.scss
    └── smartflex.min.scss
```
## Documentation

List of Classes of SmartFlex:
| Class Name  | CSS (SCSS)         | Definition         | 
| ----------- | ----------- | ----------- |
| .sf-flex    | `display: flex`| defines a flex container. It enables flex content. |
| .sf-inline-flex    | `display: inline-flex`  | defines flex container inline (one line)  
| .sf-jc-start | ` justify-content: start` | same as .jc-start |
| .sf-jc-end | `justify-content: end` | same as .jc-end |
| .sf-ai-start | `align-items: start` | same as .ai-start |
| .sf-ai-end | `align-items: end` | same as .ai-end |
| .sf-ac-start | `align-content: start` | same as .ac-start
| .sf-ac-end | `align-content: end` | same as .ac-end
| .jc-center    | `justify-content: center`|  items are centered along the line   
| .jc-sa   | `justify-content: space-around`   |     items are evenly distributed in the line with equal space around them. Note that visually the spaces aren’t equal, since all the items have equal space on both sides
| .jc-sb    | `justify-content: space-between`   | items are evenly distributed in the line; first item is on the start line, last item on the end line
| .jc-se   | `justify-content: space-evenly`  |   items are distributed so that the spacing between any two items is equal. 
| .jc-start   | `justify-content: flex-start`   | items are packed toward the start of the flex-direction
| .jc-end   | `justify-content: flex-end`  | items are packed toward the end of the flex-direction   
| .jc-stretch | `justify-content: stretch` | Stretch 'auto'-sized items to fit the container
| .jc-left | `justify-content: left ` | items are packed toward left edge of the container
| .jc-right | `justify-content: right` | items are packed toward right edge of the container
| .ai-auto    | `align-items: auto`   | automatic.
| .ai-stretch   | `align-items: stretch`    |  stretch to fill the container 
| .ai-start   | `align-items: flex-start`    | items are placed at the start of the cross axis. The difference between these is subtle
| .ai-end   | `align-items: flex-end `   | items are placed at the end of the cross axis. The difference again is subtle
| .ai-center   | `align-items: center`    | items are centered in the cross-axis
| .ai-baseline   | `align-items: baseline `   | items are aligned such as their baselines
| .as-auto    | `align-self: auto`   | automatic.
| .as-stretch   | `align-self: stretch`    |   stretch to fill the container (itself)
| .as-start   | `align-self: flex-start`    | items are placed at the start of the cross axis. The difference between these is subtle (itself)
| .as-end   | `align-self: flex-end `   | items are placed at the end of the cross axis. The difference again is subtle (itself)
| .as-center   | `align-self: center`    | items are centered in the cross-axis (itself)
| .as-baseline   | `align-self: baseline `   | items are aligned such as their baselines (itself)
| .ac-stretch    | `align-content: stretch`   | lines stretch to take up the remaining space
| .ac-start   | `align-content: flex-start`    |  items packed to the start of the container. 
| .ac-end   | `align-content: flex-end`    | items packed to the end of the container
| .ac-center   | `align-content: center `   | items centered in the container
| .ac-sa   | `align-content: space-around`    | items evenly distributed with equal space around each line
| .ac-sb   | `align-content: space-between `   | items evenly distributed; the first line is at the start of the container while the last one is at the end
| .ac-se | `align-content: space-evenly` | items are evenly distributed with equal space around them
| .ac-baseline | `align-content: baseline` | aligns the alignment baseline of the box’s first or last baseline set with the corresponding baseline in the shared first or last baseline set of all the boxes in its baseline-sharing group.
| .dir-row   | `flex-direction: row`    |  left to right; right to left.
| .dir-column   | `flex-direction: column `   | top to bottom; bottom to top.
| .dir-r-rev   | `flex-direction: row-reverse`    | right to left in; left to right.
| .dir-c-rev  | `flex-direction: column-reverse`   | bottom to top; top to bottom;
| .sf-wrap   | `flex-wrap: wrap`    | all items will be on one line
| .sf-nowrap  | `flex-wrap: nowrap `   | items will wrap onto multiple lines from top to bottom.
| .sf-w-rev   | `flex-wrap: wrap-reverse`    | items will wrap onto multiple lines from bottom to top.
| .flex-def   | `flex: 0 0 auto`    | Default value
| .flex-auto   | `flex: auto `   | same as `.sf-fill`
| .flex-none  | `flex: none `   | same as `.flex-def`
| .flex-25   | `flex: 25%`    | sets the flexible length to 25%
| .flex-50  | `flex: 50%`   | sets the flexible length to 50%
| .flex-75   | `flex: 75%`    | sets the flexible length to 75%
| .flex-100  | `flex: 100% `   | sets the flexible length to 100%
| .sf-fill  | `flex: 1 1 auto`    | automatic.
| .sf-grow-0  | `flex-grow: 0`   | Default Value
| .sf-grow-1  | `flex-grow: 1`    | Grow to 1
| .sf-shrink-0  | `flex-shrink: 0 `   | Default Value
| .sf-shrink-1  | `flex-shrink: 1`    | Shrink to 1
| .sf-order-1st  | `order: -1`   | Ordered to 1st side
| .sf-order-0  | `order: 0`    | Default Value
| .sf-order-1  | `order: 1`   | Ordered to 1
| .sf-order-2  | `order: 2`    | Ordered to 2
| .sf-order-3  | `order: 3`   | Ordered to 3
| .sf-order-4  | `order: 4`    | Ordered to 4
| .sf-order-5  | `order: 5`   | Ordered to 5
| .sf-order-6  | `order: 6`    | Ordered to 6
| .sf-order-7  | `order: 7`   | Ordered to 7
| .sf-order-8  | `order: 8`    | Ordered to 8
| .sf-order-9  | `order: 9`   | Ordered to 9
| .sf-order-last  | `order: 10`    | Ordered to last side (10)
| .sf-basis-def   | `flex-basis: 0 0 auto`    | Default Value
| .sf-basis-fill  | `flex-basis: 1 1 auto` | Automatic
| .sf-basis-25   | `flex-basis: 25%`    | specifies the initial length to 25%
| .sf-basis-50  | `flex-basis: 50%`   | specifies the initial length to 50%
| .sf-basis-75   | `flex-basis: 75%`    | specifies the initial length to 75%
| .sf-basis-100  | `flex-basis: 100% `   | specifies the initial length to 100%

## Issues and Pull Requests
If you want to add issues, click [here](https://github.com/Smart-Flex-Framework/smartflex/issues/new/choose) to submit your issue <br/>
If you want to add Pull Requests, click [here](https://github.com/Smart-Flex-Framework/smartflex/compare) to create pr

## Creators
**ArsenTech**
- https://github.com/ArsenTech

> GitHub [Smart-Flex-Framework](https://github.com/Smart-Flex-Framework) &nbsp;&middot;&nbsp;
> [SmartFlex's Website](https://smart-flex-framework.github.io) &nbsp;&middot;&nbsp;
> [ArsenTech's Subreddit](https://www.reddit.com/r/ArsenTech/)
