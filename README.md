# Ravelry Table

My submission for the [2025 Table Contest](https://posit.co/blog/announcing-the-2025-table-and-plotnine-contests/)!

## The idea

[Ravelry](ravelry.com) is a website for fibre artists to track and plan their projects as well as browse and sell knitting or crochet patterns. Ravelry has a "hot right now" section is features the patterns with the most visits in the last 24 hours. This list is a nice way to see what's trending but to view any pattern details you have to go in and click on each pattern.

In this table I fetch the Ravelry "hot right now" top 20 and present pattern details in a convenient and easy to read table so fibre artists can quickly decide if they're interested in a pattern.

## Technical details

I used the [`ravelRy`](https://github.com/walkerkq/ravelRy/) R package by Kaylin Pavlik to easily access the Ravelry api. I wrote some R code to fetch the 20 top "hot right now" patterns, fetch additional details about the patterns and their designers, and used the `gt` package to display the results in a beautiful table hosted in a Quarto dashboard with GitHub pages.

## Further work

I've played with the Ravelry API before! Check out my [R-Ladies Ottawa 2025 data hackathon submission](https://github.com/alexmcsw/ravelry-in-review) where I examined my own knitting data in a quarto dashboard.