# 🎧 genzplyr x Spotify Vibes"

**Welcome to the most unserious serious data analysis you'll ever see.**  
We're mixing Spotify data with *pure Gen Z chaos energy* using [`genzplyr`](https://hadley.github.io/genzplyr/) — the parody cousin of `dplyr` nobody asked for but everyone needed.  

---

## 🪩 What's this about?

This repo holds a Quarto vignette that uses the `moderndive::spotify_by_genre` dataset to show off five `genzplyr` examples.  

Each example comes with:
- **Translator mode:** so you know what the "grown-up" `dplyr` code would be.
- **Two explanations:** one in fluent Gen Z and one in normal English (for your data-science prof or future self).
- **Actual analysis:** averages, filters, visualizations, the works — but spiced up with slang.

---

## 💻 The vibe check (aka install instructions)

If you wanna recreate this magic:

```r
# One-time setup
install.packages("moderndive")
install.packages("tidyverse")
install.packages("pak")
# Install genzplyr from GitHub
pak::pak("hadley/genzplyr")
````

Then open the Quarto file and hit that **Render** button like it's the drop in your favorite track.

---

## 🎤 What's inside

| File                   | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `vignette.qmd` | The main Quarto analysis, packed with slang and side-eye comments. |
| `README.md`            | You're reading it, bestie.                                         |

---

## 🔥 Example moments

Here's the energy you'll find inside:

* `squad_up(track_genre)` — same as `group_by()`, but now we're forming a crew.
* `no_cap(mean_popularity = mean(popularity))` — summarize without lying.
* `slay(desc(avg_popularity))` — sort by who's serving the biggest numbers.
* `yeet()` — toss the boring stuff.
* `glow_up()` — add new columns that just *hit different*.

---

## 🧠 English translation

If all that slang gave you whiplash:

This is a demonstration of how `genzplyr` mirrors `dplyr` functions using Gen Z expressions. It explores Spotify genre data to summarize and visualize patterns in popularity, danceability, and energy levels.

---

## 💅 Credits

* Data from [`moderndive::spotify_by_genre`](https://moderndive.github.io/moderndive/reference/spotify_by_genre.html)
* Slang-coded functions from [`genzplyr`](https://hadley.github.io/genzplyr/)
* Inspiration: [Hadley Wickham LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7392344360383787008/), my personal assistant ChatGPT, Culture Coffee, chaos, and too much TikTok

---

## 🧩 TL;DR

This project:

* Yeets boring analysis.
* Glows up your R code.
* Slays with reproducible style.

So knit it, laugh, and remember: *data science doesn't have to be mid.*
