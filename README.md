# Shifts in the Beatles' Language Use Across Their Albums

A corpus project analyzing how the Beatles' lyrical language evolved across their 12 studio albums, 
using computational text analysis methods.

## Overview

The project examines whether the Beatles' musical and thematic evolution is reflected through significant changes 
in their language use. Using a lyrics corpus scraped from Genius API, the project applies corpus statistics, tf-idf 
vectorization, clustering, and semantic word embeddings to track lexical shifts from their earliest recordings to their
final album. 

## Methods
* Corpus construction - lyrics scraped via LyricsGenius
* Text cleaning - regex preprocessing, stopword removal
* Type-Token Ratio (TTR) - lexical diversity per album over time
* TF-IDF + KMeans clustering - album distinctiveness and grouping
* PCA  - 2D reduction of  and semantic vectors
* Close readings - qualitative analysis of selected songs anchored by quantitative findings

## Key Findings
* TTR generally increases across the Beatles' discography; their lexical diversity grows over time.
* Sgt. Pepper's and Magical Mystery Tour isolate themselves in tf-idf clustering because their vocabulary is uniquely distinct compared to the rest of their catalog.
* Early and late Beatles share surface-level vocabulary, but diverge semantically.
* Close readings of "Twist and Shout," "Norwegian Wood," "Being for the Benefit of Mr. Kite!," "I Want You (She's So Heavy)," and "I Am the Walrus" grounds analyses in the actual lyrics.
