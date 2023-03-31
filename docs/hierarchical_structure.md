#How to create hierarchical model

The image below shows the hierarchical model
![](https://github.com/mycodeblossom/resources/blob/master/Neat/hierarchical_structure_model.png?raw=true)
## Home page - how to define the structure

The theme supports structure for the posts:
* categories
* sub-categories


In order to use that view for the home page, it should be defined as follows:
## Create internal tags:
1. Category tag
    * Name: #subcategory
    * Slug: hash-subcategory
2. Subategory tag
    * Name: #category
    * Slug: hash-category

## Create Category/ Sub-category post

1. Create new post
2. Select name and slug
    * Name: 42-visualization
        * 42 is optional
        * 4 row, 2 column
        * helps to navigate and uniquely identify
    * Add HTML cell with : `Visualization`
        * this is the display on the home page
3. Select tag
    * #category
    * #subcategory

## Link sub-category to category

1. Select sub-category post
2. Add Category tag after the #subcategory tag

## Link post to category/sub-category
1. Create new post
2. Select tag - #subcategory tag