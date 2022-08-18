<h1 align="center">Stable Diffusion Akashic Records</h1>

<p align="center">
  <i>"Sic itur ad astra"</i><br><br>
  <b>A compendium of information regarding Stable Diffusion (SD)</b>
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

### Stable Diffusion

To use SD, you need to send a message in a channel labeled #dream-N (N being a number between 1 and 50).<br>
Your message should be structured like this : `!dream "<prompt>"`

Keep in mind the following :
- Your prompt must be 75 tokens or less, anything above will result in "prompt truncated after tokenization"
- Your prompt is case insensitive
- There's about 30,000 tokens understood by the AI, this means it won't know about some weird word unused since the 1600s
- A token is roughly a word, a punctuation, or a Unicode character
- You can see how many tokens were used by adding `-t` after / before your prompt
- Don't do prompts that would make your mother ashamed
- Guns, war, blood, historical events and celebrities are OK
- Nude big titty goth gf, gory decapitation are not. Use your own GPU.
- Same prompt, same seed, same modifiers will end with the same result
- To make variations of an image, it's recommended to keep the seed and slightly alter the prompt / modifiers

### Guides

:small_blue_diamond: [Stable Diffusion
Ultimate Beginner’s Guide](https://docs.google.com/document/d/1sgXAnFMEfx-I_Harts7cEGEPAtmWGvl62yJHByPE0ZI/edit)<br>
:small_blue_diamond: [SD Launch Presentation](https://www.youtube.com/watch?v=EqTLkt-Ycwo)<br>
:small_orange_diamond: [The DALLE-2 Prompt Book](https://dallery.gallery/wp-content/uploads/2022/07/The-DALL%C2%B7E-2-prompt-book-v1.02.pdf)<br>
:small_blue_diamond: [Creating cute animals with SD](https://youtu.be/vzV_V4AYPAA)<br>
:small_blue_diamond: [Exactly How Stable Diffusion Generates Art](https://youtu.be/a_kH32gWm2I)<br>
:small_blue_diamond: [Seed Editing](https://github.com/Maks-s/sd-akashic/blob/master/guides/richservo-seed-guide.md)<br>
:small_blue_diamond: [SD Tips](https://docs.google.com/document/d/1K6EqcsRut0InU-8jB0yOvBMGesf5Dndg5FwyuaYLqNc/edit) (csunberry#0594)<br>

## Studies [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)
A study is the same seed with slightly different prompts / modifiers. It's mainly used to understand the impact of a word/modifier on the final result. It **must** contains the resulting images

### Modifiers
:small_blue_diamond: [CFG modifier studies](https://docs.google.com/spreadsheets/d/1SYQhyJaKkkY0cmPd0WQvPwEX188l5FZxzukkC7IQDw4/htmlview)<br>
:small_blue_diamond: [Sampler studies](https://docs.google.com/spreadsheets/d/1LBsL0GcCTudXx8X0LjnD-ja6udyq-RMXBFuJG9fSvpA/htmlview)<br>
:small_blue_diamond: [Iban's Image size animation study](https://twitter.com/1ban3gaNa/status/1556987264571506690)<br>
:small_blue_diamond: [ESoS' Image size study](https://twitter.com/endlesscofstars/status/1556816377964425217)<br>
:small_blue_diamond: [ESoS' Steps & Sampler study](https://twitter.com/endlesscofstars/status/1556457377305505793)<br>
:small_blue_diamond: [ESoS' CFG study](https://twitter.com/endlesscofstars/status/1556290783992418304)<br>
:small_blue_diamond: [Chris Allen's CFG animation study](https://twitter.com/zippy731/status/1556821468184338433)<br>
:small_blue_diamond: [Localstarlight's CFG animation study](https://github.com/Maks-s/sd-akashic/blob/master/img/localstarlight-cfg-animation-study.gif) (localstarlight#3529)<br>

### Keywords
:small_blue_diamond: [Fruit basket study](https://docs.google.com/spreadsheets/d/1735ENCmaF-K8XRWjSE6ndOCvRlCMBA27qR3iPH1IHgE/htmlview) (burnin#2452)<br>
:small_blue_diamond: [Park bench study](https://docs.google.com/spreadsheets/d/1WCNQPNa56ni_S4y82bdr5xbJsBM7_VmTcioMizxRPPA/htmlview) (burnin#2452)<br>
:small_blue_diamond: [Camera study](https://docs.google.com/document/d/1c06KHlS0A7E4hCCFNl_6umuguHJQfn0K7P_h-8bDwkA/edit) (Mr_Sumato#3369)<br>
:small_blue_diamond: [SD emojis study](https://docs.google.com/document/d/1SNBoEgY5Z3x7A_3iiFL6LQCnK2FtVF63CEJo4G_brz4/edit) (Spake#1808)<br>
:small_blue_diamond: [4 Games Cafeteria study](https://twitter.com/bs_blackscout/status/1560128847508537344)<br>

### Misc
:small_blue_diamond: [Multilingual capabilities study](https://jalonso.notion.site/Stable-Diffusion-Language-Comprehension-5209abc77a4f4f999ec6c9b4a48a9ca2)<br>
:small_blue_diamond: [Stable Diffusion Prompt Weighting study](https://drive.google.com/file/d/111p6ObWFFKo1aZbuiIyGRZI4fBMHtN6s/view)<br>
:small_blue_diamond: [160 celebrities study](https://docs.google.com/spreadsheets/u/0/d/1IqXkYDXux97aU8Y5kqqBrBvCn3CLRDhMZ7lEWsAtwUc/htmlview)<br>
:small_blue_diamond: [One Hundred TV shows study](https://jalonso.notion.site/Stable-Diffusion-One-hundred-TV-shows-e490780c49724cee987cd6bf89b37c4c)<br>
:small_blue_diamond: [Film studies](https://artblind.notion.site/artblind/3e50796fe6904048981156436145d501)<br>
:small_blue_diamond: [Punctuation study](https://arkitecc-prompt-study.notion.site/adecfbad9c7c49ddb0eba8795d96efd4)<br>
:small_blue_diamond: [Secondary artist study](https://www.youtube.com/watch?v=-P15nYxRQJg)<br>
:small_blue_diamond: [Prompt permutation study](https://erucipe.notion.site/Prompt-permutation-study-1b6c569f6218445f8a1d4598930fed09)<br>
:small_blue_diamond: [Artist order study](https://www.figma.com/proto/LOtGvO8x6KZFQclXBGLxUb/Stable-Diffusion-test?scaling=scale-down) ([Kitt Hirasaki](https://www.reddit.com/user/Cultural_Contract512/))<br>

## Art style/Artist lists [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: [Suburban House, Art styles](https://github.com/Maks-s/sd-akashic/blob/master/img/suburban-house.png)<br>
:small_blue_diamond: [Stable Diffusion Artist Studies](https://proximacentaurib.notion.site/e2537cbf42c34b7e9a9a4126f81dfd0d)<br>
:small_blue_diamond: [SD Artist Collection](https://sgreens.notion.site/sgreens/4ca6f4e229e24da6845b6d49e6b08ae7) (SGreen#2222)<br>
:small_blue_diamond: [Bacontime's Artist comparisons, part 1](https://github.com/Maks-s/sd-akashic/blob/master/img/bacontime-artist-comparison.png) (bacontime#6072)<br>
:small_blue_diamond: [Bacontime's Artist comparisons, part 2](https://github.com/Maks-s/sd-akashic/blob/master/img/bacontime-artist-comparison-2.png) (bacontime#6072)<br>
:small_blue_diamond: [SD Styles & Mediums](https://docs.google.com/document/d/1ZtNwY1PragKITY0F4R-f8CarwHojc9Wrf37d0NONHDg/edit)<br>

## Keyword lists [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: [Artists, Keywords, Art styles known to work with text to image](https://docs.google.com/document/d/1SaQx1uJ9LBRS7c6OsZIaeanJGkUdsUBjk9X4dC59BaA/edit)<br>
:small_orange_diamond: [Offhand's Disco Diffusion Prompt Keywords](https://docs.google.com/spreadsheets/d/1j7zaDi_PkndizQ2pL8B_yMcwfKUdE6tSMhL31bYtJNs/htmlview)

## Misc [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)

:small_blue_diamond: [Image dimension table](https://github.com/Maks-s/sd-akashic/blob/master/img/brbbbq-dimensions.png) (brbbbq#0731)<br>
:small_blue_diamond: Image to prompt : [CLIP Interrogator](https://colab.research.google.com/github/pharmapsychotic/clip-interrogator/blob/main/clip_interrogator.ipynb)<br>
:small_blue_diamond: [SD Image splitter](https://sd-split.pages.dev/)<br>
:small_blue_diamond: [List of 1.5m SD prompts](https://drive.google.com/file/d/1pZHtL43Gk2SGFTTP-XXDOBEGyBL9BS73/view)<br>
:small_blue_diamond: [List of 9m SD prompts with their results](https://drive.google.com/u/0/uc?id=14_CRrWMw20OSSd5ZA-7epXdWF3DlwM8g)<br>
:small_orange_diamond: SD's Dataset search : [CLIP retrieval](https://rom1504.github.io/clip-retrieval/)<br>
:small_orange_diamond: [Prompt builder](https://promptomania.com/stable-diffusion-prompt-builder/)<br>
:small_red_triangle: [Camera distance terms](https://github.com/Maks-s/sd-akashic/blob/master/img/camera-distance-terms.jpg)<br>

## Prompts [<sup><sup>[ToC]</sup></sup>](#notebook_with_decorative_cover-table-of-contents)
Here's a list of quick prompts to get you started in the world of Stable Diffusion

:small_blue_diamond: GTA V cover character : `[subject] in GTA V, cover art by Stephen Bliss, artstation`<br>
:small_blue_diamond: Quick photorealism (NOP#1337) : `[prompt], Canon EOS R3, f/1.4, ISO 200, 1/160s, 8K, RAW, unedited, symmetrical balance, in-frame`<br>
:small_blue_diamond: Age changer (richservo#8465) : `DSLR photo portrait still of [age] year old age [age] [person] at age [age]!!!, 85mm f1.8`<br>
:small_blue_diamond: Film character (richservo#8465) : `film still of [character] [action] in [movie], 4k`<br>
:small_blue_diamond: Real life cartoon character (richservo#8465) : `portrait photo still of real life [character], 8k, 85mm f1.8`<br>
:small_blue_diamond: Dish picture (richservo#8465) : `DSLR food photograph of [dish description], 85mm f1.8`<br>
:small_blue_diamond: Muppet portrait (richservo#8465) : `studio portrait still of muppet !!!!![person or character] !!!!!! as a muppet muppet as a muppet, 8k, studio lighting, key light -C 13 -s 150` <br>

