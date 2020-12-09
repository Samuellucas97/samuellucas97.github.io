# About Me

I do software research.  My students and I create tools and techniques that **help developers build better software**&mdash;by automatically testing, analyzing, and debugging its code and its development process.

Our approaches have proven quite influential in academia and industry.  My [Curriculum Vitae](assets/ZellerCV.pdf) lists the most important achievements.


## Latest News from [@AndreasZeller](https://twitter.com/AndreasZeller)

<a class="twitter-timeline" data-lang="en" data-height="300" data-width="350" data-chrome="noheader nofooter noborders transparent"
href="https://twitter.com/AndreasZeller" data-dnt="true">Tweets by AndreasZeller</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 


## Current Projects

Our **research projects** involve generating software tests, automated debugging and repair, analyzing mobile systems, analyzing user interfaces, and more; see our papers below for details.  Our **solutions** typically apply and combine several techniques including dynamic analysis, static analysis, specification mining, test generation, natural language processing, machine learning, and formal languages.

My largest project in 2020 was [The Fuzzing Book](https://www.fuzzingbook.org/)&mdash;an interactive textbook on test generation ("fuzzing") techniques.  You can execute and edit the code right in your browser.  For 2021, I am working on a sibling project, called "The Debugging Book", and exploring automated debugging techniques. Stay tuned!


## Current Papers

My papers can be found on [Google Scholar](https://scholar.google.com/citations?user=-Qytr_YAAAAJ&hl=en&oi=ao), in the [ACM Digital Library](https://dl.acm.org/profile/81100307506), and in [DBLP](https://dblp.uni-trier.de/pers/z/Zeller:Andreas.html). For recent works and preprints, check out my [CISPA publication list](https://cispa.saarland/people/zeller/).


## Current Courses

In Winter 2020/21, we offer an [advanced course on automated debugging](https://cms.cispa.saarland/debug/).  
For Summer 2021, we plan to offer an _advanced course on security testing_ and a _seminar around automated testing and debugging_.

Check out our courses [here](https://cms.cispa.saarland/).


## My Group

At CISPA and Saarland University, I work with [great students and Post-Docs from across the world](Group.html) on cutting-edge research.

We are constantly looking out for great students and Postdocs.  Our positions are well paid and allow for highly productive research.  If you're interested in a PhD or Postdoc position, please [apply at CISPA](https://www.cispa.saarland/) and state your specific interests.


## Theses

If you are a student of Saarland University and have fun with automated program analysis, testing, and debugging, you might want to do a thesis with us.  [Here are the details on how to do a thesis with us.](Theses.html)


## My Blog

My [blog](Blog.html) has a mixture of various topics from academia and software development, often with a humorous touch.  Here is a selection of popular posts:

<ul>
  {% for post in site.posts %}
  {% if post.tags contains "popular" %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      (<span class="date">{{ post.date | date: "%Y-%m-%d" }}</span>)
    </li>
  {% endif %}
  {% endfor %}
</ul>

[All blog posts](Blog.html)


## Watch Me

I am a frequent speaker at events. Here are two recorded talks I am particularly proud of.

### 2020: Learning the Language of Failure

In my 2020 CASA Distinguished Lecture ["Learning the Language of Failure"](https://www.youtube.com/watch?v=3ZW1DI2PxvI), I show some highlights of our current work:

* how to automatically learn circumstances of a given failure, expressed over features of input elements;
* how to automatically infer input languages as readable grammars, and how to use them for massive fuzzing; and
* how to systematically and precisely characterize the set of inputs that causes a given failure – the "language of failure".

Enjoy the show! [Annotated slides](assets/CASA-2020-Learning-the-Language-of-Failure.pdf) are available, too.

### 2018: Outstanding Research Award Keynote

These days, I also spend quite some time giving career advice. In my [ICSE 2018 SIGSOFT Award keynote](https://www.youtube.com/watch?v=U5jLjcxnwfU), I
unfold three lessons on _impact in software engineering research_:

1. Do relevant work
2. Strive for simplicity
3. Keep on innovating

Again, detailed [slides and full manuscript](assets/ICSE-2018-Keynote-Zeller.pdf) are available.


## Stay Tuned

All relevant events regarding current work are [posted on Twitter](https://twitter.com/AndreasZeller).

<a href="https://twitter.com/AndreasZeller?ref_src=twsrc%5Etfw" class="twitter-follow-button">Follow @AndreasZeller</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<small>I do not collect any data from this site, but Twitter does. See the <a href="https://twitter.com/en/privacy">Twitter privacy policy</a>
for details</small>.