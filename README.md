
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

project-axel-1

## Summary

Building AI course project. My idea to solve a real world problem with AI. 

## Background

As a future university student I find it hard to get the right information about different universities, especially universities in other countries than my own (Sweden). There is no truly up-to-date website with all relevant information about universities/colleges. I want a place where it's easy to find the right statistics from all major universites/colleges. It should be easy to get an understanding of the student- and day to day-life, how to apply and what qualifications that is needed.

The major problems is:
* It's hard to find relevant information about universities and colleges.
* It's hard to know how and when to apply.
* There is no easy way to get relevant information about universities/colleges outside of homecountry.


## How is it used?

A website where you can write the name of a university/college and you will get an instant description about student-life, location, short history, global and national ranking. You will also get aa list of all different subject/courses that you can attend at that specific school, where you can click to get information about the specific course. The information will include ranking, number of students, entry qualifications, meritourious qualifications, chance of job whitin 1 year of graduating, normal jobs of graduates, intensity of the course, competition and when application opens and closes. 

You will also be able to choose a geographical location or other criteria such as subject, student-life, chance of a job after graduation and so on and see the highest ranking universities/colleges within your criteria. You will be able to combine different criterias such as "best university in Italy for economy".

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
