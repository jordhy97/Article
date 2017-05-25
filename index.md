## What is Interpolation?

In engineering and science, it is often required to estimate data points in-between a given discrete set of data points that is obtained from sampling and experiment. The method to estimate or construct these new data points is called **interpolation**. **Interpolation** derives a function from a set of discrete data points that passes through all the given data points. The function derived from interpolation depends on the interpolation methods used. 

In addition to estimate data points, interpolation is also used to approximate a complicated function by a simple function. The simple function can be obtained by making an interpolation from a few data points evaluated from the original function. Although this simple function have interpolation errors, depending on the problem domain and the interpolation method used, the gain in simplicity may be better than the loss in precision from errors.

There are a lot of interpolation methods that can be used to estimate data points. When choosing an appropiate interpolation method for a problem, there are some things that need to be considered, like how accurate is the method, how expensive (complex) is it, how smooth is the interpolant, and how many data points are needed. In this article, the interpolation methods that will be discussed are the commonly used ones because of its simplicity, they are:
- [Nearest-Neighbour Interpolation](#nearest-neighbour-interpolation)
- [Polynomial Interpolation](#polynomial-interpolation)
- [Linear Interpolation](#linear-interpolation)
- [Spline Interpolation](#spline-interpolation)

## Nearest-Neighbour Interpolation

**Nearest-neighbour interpolation** (also known as **proximal interpolation**) is the simplest interpolation method. Rather than calculate an average value by some criteria or generate value based on complicated rules, this method locates/selects the value of the nearest data point and assign that value. Because this method only considers the nearest point it is also called **piecewise constant interpolation**. 

Although this method is unlikely to be used in simple problems because there are other methods that are almost as simple to implement but overall better than this method, this method is a favourable choice over the other methods in high-dimensional multivariate interpolation (interpolation in functions that contain more than one variable) because of its speed and simplicity. This method is commonly used in real-time 3D rendering to select color values for a textured surface. 

Another application of this method is to scale up an image in image processing. But there is a major drawback in using this method for image processing. It tends to generate images of poor quality.

## Polynomial Interpolation

## Linear Interpolation

## Spline Interpolation

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jordhy97/Article/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
