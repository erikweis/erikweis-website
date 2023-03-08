---
title: Emergent Music
summary: What do complex systems sound like?
tags:
  - Music
  - Other
#date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
{{< toc >}}
Recently, generative AI models have made massive strides in producing completely realistic music trained on data.
While those gains are fascinating and impressive, the music produced by these models is constrained (to some extent) by the music used to train the models.
This music was produced by humans, or AI models in the style of humans.

Rather, could we describe a mechanistic model that produces interesting or pleasing music? 
There are many reasons to believe we could, owing the phenomenal amount of regularity in existing music.
These patterns span spatial and temporal scales of music.

# Spatial and temporal patterns in music

The spatial scale is the land of harmony. How do notes fit together in pleasing ways?
Nature has given us a head start via the harmonic series. Intervals like the octave, perfect fifth, and perfect fourth sound beautiful to us, and for the basis for western music. Before the 16th century
[^story_of_music] and the music of [], thirds weren't used in western music
These relationships are 

But there are all sorts of ways to describe the space of note combinations by comparing pairs of 2, 3, etc. notes., such as this torus that connects notes that are seperated by a minor third (green), major third (red), or a fifth (blue).
![extended tonality](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTVrbeA0esLm02Nsxaxdm78bj49k6gZOcYy_WmOBuxO2bVoK63OwdGgd4lVJcxjHcQ_J6w&usqp=CAU)


For example, classical music has a firmly constrained set of "allowable" chord progressions.
![Chord progressions in classical music](https://globalguitarnetwork.com/wp-content/uploads/2014/05/Chord-Motion_Major-Key.png)

## Mathematical models of temporal dynamics

- markov models
- you could infer this

## Mathematical descriptions of harmony space

- 


# Generative music

A model describes the probability of 

$$P(x(t) | x(t-1),\dots,x(0)) = P(x_1)P(x_2)\ldots P(x_n)$$



There's also


Alternatively,
consider the case where

Music generation in this way is limited by the styles of that which came before.

[^story_of_music]: The story of music.

{{< bibliography path/to/bib.json >}}