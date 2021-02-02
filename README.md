# Steam Image Search

The goal of this repository is to search for images on [Steam][steam-store] using natural language queries.

## Data

The dataset consists of 29,982 vertical images (300x450 resolution), downloaded from [Steam][steam-store].

Image features have been pre-computed, using OpenAI's [CLIP][openai-clip] model based on [Vision Transformer][google-vit] architecture.

## Usage

Run [`steam_image_search.ipynb`][colab-notebook].
[![Open In Colab][colab-badge]][colab-notebook]

## Results

Below are shown results for:
-   [image search][results_image_search], i.e. using natural language queries,
-   [reverse image search][results_reverse_image_search], i.e. using image queries.

### Image Search

![Results A](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_A.jpg)

![Results B](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_B.jpg)

![Results C](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_C.jpg)

![Results D](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_D.jpg)

![Results E](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_E.jpg)

### Reverse Image Search

![Reverse A](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/reverse_A.jpg)

![Reverse B](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/reverse_B.jpg)

## References

- [`steam-CLIP`][banner-repository-CLIP]: retrieve games using image queries,
   - interactive exploration with a web app [using an appID][web-app-using-id],
   - interactive exploration with a web app [using a dropdown menu][web-app-using-text].
- [`steam-image-search`][natural-language-search]: retrieve games using natural language queries,

<!-- Definitions -->

[steam-store]: <https://store.steampowered.com/>
[openai-clip]: <https://openai.com/blog/clip/>
[google-vit]: <https://ai.googleblog.com/2020/12/transformers-for-image-recognition-at.html>
[colab-notebook]: <https://colab.research.google.com/github/woctezuma/steam-image-search/blob/main/steam_image_search.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[results_image_search]: <https://github.com/woctezuma/steam-image-search#image-search>
[results_reverse_image_search]: <https://github.com/woctezuma/steam-image-search#reverse-image-search>
[banner-repository-CLIP]: <https://github.com/woctezuma/steam-CLIP>
[web-app-using-id]: <https://damp-brushlands-51855.herokuapp.com/render/1091500/>
[web-app-using-text]: <https://woctezuma.github.io/steam-svelte-autocomplete/index.html>
[natural-language-search]: <https://github.com/woctezuma/steam-image-search>
