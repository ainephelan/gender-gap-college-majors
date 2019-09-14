# Visualising the Gender Gap in College Majors

Today I'm going to look at creating visualisations which communicate the historical narrative of the gender gap in different fields of study in the US.

I'll use the already cleaned data set described below, and I'm going to take the opportunity to practice some techniques to eliminate [chartjunk](https://en.wikipedia.org/wiki/Chartjunk) and maximise the [data-ink ratio](https://infovis-wiki.net/wiki/Data-Ink_Ratio).  I want these visuals to be communicative and complete, not requiring any ancillary data to be understood.

All the better to see you with my dear!

### Context
The [National Center for Education Statistics](https://nces.ed.gov/programs/digest/current_tables.asp) in the US releases a data set annually containing the percentage of bachelor's degrees granted to women since 1970. The data set is broken up into 17 categories of degrees, with each column as a separate category.

[Randal Olson](http://www.randalolson.com/2014/06/14/percentage-of-bachelors-degrees-conferred-to-women-by-major-1970-2012/), a data scientist from the University of Pennsylvania, has cleaned the data set for years 1970 to 2012 and made it available on his personal website. 

Gender parity is a topic close to my own heart, and we still have a long way to go in understanding it or in some instances even [agreeing that it exists](https://www.smartcompany.com.au/business-advice/politics/frydenberg-pay-gap-closed/), let alone bridging it.

Right, let's use Randal's [cleaned data](http://www.randalolson.com/wp-content/uploads/percent-bachelors-degrees-women-usa.csv) to see some historical differences between the genders regarding their chosen fields of study in the US.

For the purposes of this analysis I'll be treating gender as a binary construct only.
