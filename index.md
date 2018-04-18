## Guiding Principles

Make this website as minimal as possible.

Mental mode: motivating example + concept ( pedestrian level) >>> math formula >>> code ( so we can implement) 


## Model Eval Metrics

### Recommendation Systems

Main metrics typically ranking measures which are i) MAP ( mean average precision) ii) NDCG ( normalized discounted cumulative gain)



```markdown
Toy Example:

Input: movie - recently watched
Output N movies - to watch next

How do we score the recommendation?

Requirements:
- relevance matters: Chosen ( Yes or no)  we want to make sure the user chooses the recommendation
- order matters: Higher the better. Imagine google search showing the best 5 at the bottom of the page vs the top of the page.
- variety/ choice matters: Somestimes a recommendation engine may want to give a couple of options instead of just one option

Formula:

Toy example:

Recommendation, Chosen, Precision
A,1, 1/1
B,0, 
C,1, 1+1 / 3
D,1, 1+1+1 / 4

Math:
precision per item: cumulative items chosen / items position
Average precision : sum ( precision per item) / sum ( items chosen)
Mean average precision : sum(average precision across recommendations shown) / sum ( recommendations shown)

Code: 

Mean Average Precion

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

Resources:
- [Best example on metrics definiton](https://makarandtapaswi.wordpress.com/2012/07/02/intuition-behind-average-precision-and-map/).

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/david-woo-instacart/easyml.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
