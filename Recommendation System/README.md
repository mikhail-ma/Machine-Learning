# Recommendation System

Development of a recommendation service that will return posts for each user at any time based on previously liked texts.

The quality of the written service is evaluated in a checker based on hidden data. The set of users is fixed and no new ones will appear. Application should process the request in less than 0.5 seconds.

Posts can remain relevant for several months, so it makes sense to dive into the analysis of the texts themselves.

The idea is to use [Cosine similarity](https://www.sciencedirect.com/topics/computer-science/cosine-similarity) is a measure of similarity between two sequences of numbers. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction. This method can be used as a measurement of how similar are posts in a given social network.

<p align="center">
  <img width="850" height="495" src="img1.jpg">
</p>

Plus some other futures: sentiment (negative, neutral and positive), word and paragraph count, and hour/month/week/weekday of publication. 

