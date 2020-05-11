# learn-web-scraping notes

- [learn-web-scraping notes](#learn-web-scraping-notes)
  - [Description](#description)
  - [Useful resources](#useful-resources)
  - [Introduction](#introduction)
    - [What is web scraping?](#what-is-web-scraping)
    - [Challenges and alterantives](#challenges-and-alterantives)

## Description

These notes were taken by [Matthew Haines](hainesm6@gmail.com) as part of learning how to scrape the web.

## Useful resources

- [HTML youtube Crash Course][html_youtube_crash_course].
- Real Python articles:
  - [Practical introduction](https://realpython.com/python-web-scraping-practical-introduction/). *Not recommended*.
  - [Beautiful soup web scraper](https://realpython.com/beautiful-soup-web-scraper-python/). *Recommended*. Forked code available at [link][real_python_materials_web_scraping_bs4].

[html_youtube_crash_course]: [https://www.youtube.com/watch?v=UB1O30fR-EE]
[real_python_materials_web_scraping_bs4]: [https://github.com/hainesm6-learning/realpython-materials/tree/master/web-scraping-bs4]

## Introduction

### What is web scraping?

- Web scraping refers to gathering data from the internet. Often this involves automation rather than manually manipulating webpages.
- Certain websites don't permit users to scrape their data. As such, it is important to **ensure you're not violating any Terms of use** before undertaking web scraping. [Violating Terms of Use risks claims being brought against you](https://www.rocketlawyer.com/gb/en/blog/to-scrape-or-not-to-scrape/).

### Challenges and alterantives

- Each website will have different HTML structures, requiring different treatments to extract the desired data.
- Websites aren't static implying methods could break after sometime.
- Consider using an **API** if available as they are designed for data exchange, generally working with structured data e.g. JSON and XML, as apposed to HTML.
