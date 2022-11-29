# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  **(R1a)** Based on the information in these pieces, why did the creators start collecting the CountLove data?


- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. **(R1b)** Please summarize the main point or argument of this article.


Next, we're going to reflect about who collected this data, and what's actually inside it.

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?


**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude?


**(R1e)** How and where does CountLove get their data about the protests?


**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation?


**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a definition of "value".)


**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder (See the Envisioning Cards)?


# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words.
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power?


**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)


**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

## Your Responses and Reflections

### Critical Analysis & Reflection: Before You Code (questions above)

* **(R1a)** The creators started documenting protest data because many protests do not make it to national headlines and therefore protest trends and social issues are not being fully documents and heard. With Count Love, this information is available in one place and highlights the issues that many people face.

* **(R1b)** This article discusses police violence against black men in America. Mainly, the article highlights the many protests that took place after the death of George Floyd. The article displays a map representation of protests that were around America and provides pictures from these many protests.
* **(R1c)** Tommy Leung and Nathan Perkins are engineers and scientists who have collected and shared the Count Love data. They are very interested in civic responsibility and public policy.

* **(R1d)** Count Love includes demonstrations that are not part of "regular business". They tend to not include awareness events, celebrations, historic reenactments, fundraising events, or political campaign rallies.

* **(R1e)** Count Love gets their data mainly from local newspapers and television sites. They are looking through these sources on a daily basis and have been covering event since 2017.

* **(R1f)** Count Love estimates the number of people who have attended a protest by recording the most "conservative" attendance number. For example, "a dozen" is 10, "dozens" is 20, and "hundreds" is 100. This estimation tactic may be problematic as it can underestimate the number of people who have attended a protest. Knowing the number of people who have attended a protest is important because it signifies how important the protest is and how many people care about it. It is an even bigger deal when the total attendance wasn't that many in the first place.

* **(R1g)** One main Value of Count Love is the importance of remembering and recoding past protests. Every protest had a deep meaning to those involved and it is very important to be able to access past protests and remember why they occurred. Further, another value of Count Love is keeping these records and information factual. There is a lot of misinformation nowadays and it is important to have a resource that people can use and view that it truthful.

* **(R1h)** A direct stakeholder of Count Love is someone who is viewing this resource and gaining information from it. An example of an indirect stakeholder is someone who doesn't use Count Love first hand, but may hear about it from someone or see data from this website being used in another source, such as the NYT article.

### Part 3: Locations (`analysis.R`)
* **(R3a)** The number of protests in Washington does not surprise me given how populated and diverse out state is. We have major cities here, such as Seattle, where people are more likely to be more interested in social change. Further, throughout the entire state of Washington there are many different views such as left or right wing so it makes sense that Washington has a lot of protests as we have so many different people and views in our state.

* **(R3b)** I think the sapply() function was pretty cool to see because of how quickly I was able to apply the function to my entire vector. It seems very efficient and quick when trying to get information on a large data set.

* **(R3c)** In the state table I noticed a lot of quality issues. This mainly includes state abbreviations not being capitalized which caused multiple state abbreviations of the same state to occur such as "WA" and "wA". I also noticed there were a lot of misspellings of state abbreviations such as "te" which makes it really difficult to know what state those protests actually belonged to.

### Critical Analysis & Reflection: After You Code (questions above)
* **(R7h)** I would say that Count Love mainly embodies the first form of challenging power. Count Love is a really amazing tool of unbiased and factual information on protests. Today, there is a lot of misinformation surrounding protests, and violence during protests, and I think Count Love is really great at providing reliable data for reasons of protests, how many people were involved, and when the protests happened. Count Love also provides their sources of where they got their information which is really great for challenging false claims people may make about protests and similar events.

* **(R7i)** I found it to be really interesting how many people show up to protests. I had never examined protest data before and I was really shocked. I also couldn't believe how many Women's marchers there were and how the biggest protest on the Count Love website is for one of the Women's marches. It is truly amazing to see how many people show up to protests.

* **(R7j)** It would be very interesting to see if these protests had any impact on legislation although that can't be done with just this data set. I also think it would be interesting to see the differences between the same protest (such as the Women's march) but in different years and see the differences in participation.
