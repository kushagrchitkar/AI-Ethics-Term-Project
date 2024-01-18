# AI Ethics Term Project: Implications of Sponsored Search Results on Amazon India

## Introduction

As part of our term project for the AI Ethics course, we conducted a comprehensive study on the implications of sponsored search results on Amazon India, the largest e-commerce marketplace. Sponsored results play a crucial role in influencing potential customers' choices on such platforms, and our study aimed to understand the dominance of sponsored spaces on the Amazon Search Engine Landscape. Specifically, we explored the competition between third-party merchants, Amazon's private labels (PLs), and special merchants (SMs) within these sponsored spaces.

## Data Collection

Utilizing web crawling techniques, we gathered recommendations and metadata for ten unique products from Amazon's website over ten days.

## Key Questions and Objectives

We sought answers to the following questions:

1. What fraction of products are Amazon Private Labels/Special Merchants among all a) Sponsored Results, b) Organic Results, and c) Sponsored + Organic results?
2. Where do Amazon Private Labels/Special Merchants appear in the sponsored results? (For SERP (Search Engine Result Page) 1 of the products)
3. What is the temporal distribution of results, and how are the cells highlighted? (For SERP 1 of the products)
4. Can we verify Amazon's claim that "Only 2-3 percent of the ad space is occupied by Private Labels"?

Additionally, we aimed to measure the exposure given to top brands and sellers using a geometric attention distribution model. Upon comparing the average user ratings for the sponsored products, a discernible trend emerges, indicating user dissatisfaction. It becomes evident that users might have inadvertently succumbed to Amazon's strategic product placement tactics. To further validate our analysis, we conducted a survey seeking insights into customer preferences regarding the purchase of a specific item based on aesthetics. The survey responses revealed a noteworthy pattern, with users expressing either indifference or a preference for third-party products over the sponsored offerings. This corroborates our initial findings and underscores the potential influence of Amazon's product placement strategies on user choices.

## Findings

### Dominance of Amazon PLs and SMs
- Significantly higher exposure was observed for SMs and PLs.
- Average user ratings for these sponsored products indicated user dissatisfaction.

### Geometric Attention Distribution Model
- The probability of clicking an item (p) influenced the attention distribution.
- Attention of a product in the ith position was calculated using $A(i) = p * (1-p)^{i-1}$.

### User Preferences
- A survey revealed that customers were either indifferent or preferred third-party products based on aesthetics.

## Documentation

All findings, analyses, and methodology details have been documented in the empirical analysis PDF and the final presentation.

Feel free to explore the detailed analysis for a comprehensive understanding of our study.

