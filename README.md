<h1 align="center">Stable Diffusion Akashic Records</h1>

<p align="center">
  <i>"Sic itur ad astra"</i><br><br>
  <b>A compendium of informations regarding Stable Diffusion (SD)</b>
</p>

<p align="center">
  <a href="https://github.com/Maks-s/sd-akashic/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true" alt="Pull Requests">
  </a>
  <a href="LICENSE.md">
    <img src="https://img.shields.io/badge/License-Unlicense-lightgrey.svg?longCache=true" alt="The Unlicense">
  </a>
</p>

****

This repository is a collection of studies, art styles, prompts and other useful tools you can use throughout your exploration of the latent space.

As Stable Diffusion is still in beta and subject to lots of changes, the Records will often change to reflect new information.

## :notebook_with_decorative_cover: Table of Contents
- **[General](#general-information-toc)**
- **[Studies](#studies-toc)**
- **[Art style/Artist lists](#art-styleartist-lists-toc)**
- **[Keyword list](#keyword-lists-toc)**
- **[Misc](#misc-toc)**
- **[Prompts](#prompts-toc)**

## General information [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

### The Records
SD is brand new. As such, not many resources exist which are solely based on it.<br>
To differentiate between other AI imagery tools and SD, the Records will use the following nomenclature :

<p>
:small_blue_diamond: Resource based on SD<br>
:small_orange_diamond: Resource based on other AI imagery<br>
:small_red_triangle: Resource not based on any AI imagery (such as photography terms)<br>
</p>

### Standard Diffusion

To use SD, you need to send a message in a channel labeled #dream-N (N being a number between 1 and 50).<br>
Your message should be structured like this : `!dream "<prompt>"`

Keep in mind the following :
- Your prompt must be 77 tokens or less, anything above will be silently ignored
- Your prompt is case insensitive
- There's about 30,000 tokens understood by the AI, this means it won't know about some weird word unused since the 1600s
- A token is roughly a word, a punctuation, or a Unicode character
- Don't do prompts that would make your mother ashamed
- Guns, war, blood, historical events and celebrities are OK
- Nude big titty goth gf, gory decapitation are not. Use your own GPU.
- Same prompt, same seed, same modifiers will end with the same result
- To make variations of an image, it's recommended to keep the seed and slightly alter the prompt / modifiers

### Guides

:small_blue_diamond: [SD Launch Presentation](https://www.youtube.com/watch?v=EqTLkt-Ycwo)<br>
:small_orange_diamond: [The DALLE-2 Prompt Book](https://dallery.gallery/wp-content/uploads/2022/07/The-DALL%C2%B7E-2-prompt-book-v1.02.pdf)<br>

## Studies [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)
A study is the same seed with slightly different prompts / modifiers. It's mainly used to understand the impact of a word/modifier on the final result. It **must** contains the resulting images

### Modifiers
:small_blue_diamond: [CFG modifier studies](https://docs.google.com/spreadsheets/d/1SYQhyJaKkkY0cmPd0WQvPwEX188l5FZxzukkC7IQDw4/htmlview)<br>
:small_blue_diamond: [Sampler studies](https://docs.google.com/spreadsheets/d/1LBsL0GcCTudXx8X0LjnD-ja6udyq-RMXBFuJG9fSvpA/htmlview)<br>
:small_blue_diamond: [Iban's image size animation study](https://twitter.com/1ban3gaNa/status/1556987264571506690)<br>
:small_blue_diamond: [ESoS' image size study](https://twitter.com/endlesscofstars/status/1556816377964425217)<br>
:small_blue_diamond: [ESoS' steps & sampler study](https://twitter.com/endlesscofstars/status/1556457377305505793)<br>
:small_blue_diamond: [ESoS' CFG study](https://twitter.com/endlesscofstars/status/1556290783992418304)<br>
:small_blue_diamond: [Chris Allen's CFG animation study](https://twitter.com/zippy731/status/1556821468184338433)<br>

### Keywords
:small_blue_diamond: [Fruit basket study](https://docs.google.com/spreadsheets/d/1735ENCmaF-K8XRWjSE6ndOCvRlCMBA27qR3iPH1IHgE/htmlview)<br>

### Misc
:small_blue_diamond: [Multilingual capabilities study](https://jalonso.notion.site/Stable-Diffusion-Language-Comprehension-5209abc77a4f4f999ec6c9b4a48a9ca2)


## Art style/Artist lists [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: [Suburban House, Art styles](https://github.com/Maks-s/sd-akashic/blob/master/img/suburban-house.png)<br>
:small_blue_diamond: [Stable Diffusion Artist Studies](https://proximacentaurib.notion.site/e2537cbf42c34b7e9a9a4126f81dfd0d)<br>
:small_blue_diamond: [SD Artist Collection](https://sgreens.notion.site/sgreens/4ca6f4e229e24da6845b6d49e6b08ae7)<br>

## Keyword lists [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: [Artists, Keywords, Art styles known to work with text to image](https://docs.google.com/document/d/1SaQx1uJ9LBRS7c6OsZIaeanJGkUdsUBjk9X4dC59BaA/edit)<br>
:small_orange_diamond: [Offhand's Disco Diffusion Prompt Keywords](https://docs.google.com/spreadsheets/d/1j7zaDi_PkndizQ2pL8B_yMcwfKUdE6tSMhL31bYtJNs/htmlview)

## Misc [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: Valid resolutions (width/height) : `64, 128, 192, 256, 320, 384, 448, 512, 576, 640, 704, 768, 832, 896, 960, 1024, 1088, 1152, 1216, 1280, 1344, 1408, 1472, 1536, 1600, 1664, 1728, 1792, 1856, 1920, 1984, 2048`<br>
:small_blue_diamond: 16:9 resolutions : `-W 512 -H 288`, `-W 1024 -H 576`<br>
:small_red_triangle: [Camera distance terms](https://github.com/Maks-s/sd-akashic/blob/master/img/camera-distance-terms.jpg)<br>

## Prompts [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)
Here's a list of quick prompts to get you started in the world of Stable Diffusion

:small_blue_diamond: GTA V cover character : `[subject] in GTA V, cover art by Stephen Bliss, artstation`<br>
:small_blue_diamond: Quick photorealism (NOP#1337) : `[prompt], Canon EOS R3, f/1.4, ISO 200, 1/160s, 8K, RAW, unedited, symmetrical balance, in-frame`

