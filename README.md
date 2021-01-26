# Steam Image Search

The goal of this repository is to search for images on [Steam][steam-store] using natural language queries.

## Data

The dataset consists of 29,982 vertical images (300x450 resolution), downloaded from [Steam][steam-store].

Image features have been pre-computed, using OpenAI's [CLIP][openai-clip] model based on [Vision Transformer][google-vit] architecture.

## Usage

Run [`steam_image_search.ipynb`][colab-notebook].
[![Open In Colab][colab-badge]][colab-notebook]

## Results

![Results A](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_A.jpg)

![Results B](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_B.jpg)

![Results C](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_C.jpg)

![Results D](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_D.jpg)

![Results E](https://raw.githubusercontent.com/wiki/woctezuma/steam-image-search/img/results_E.jpg)

<!-- Definitions -->

[steam-store]: <https://store.steampowered.com/>
[openai-clip]: <https://openai.com/blog/clip/>
[google-vit]: <https://ai.googleblog.com/2020/12/transformers-for-image-recognition-at.html>
[colab-notebook]: <https://colab.research.google.com/github/woctezuma/steam-image-search/blob/main/steam_image_search.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
