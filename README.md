# About Me

I do software research.  My students and I create tools and techniques that **help developers build better software**&mdash;by automatically testing, analyzing, and debugging its code and its development process.

Our approaches have proven quite influential in academia and industry.  My [Curriculum Vitae](assets/ZellerCV.pdf) lists the most important achievements.


## Latest News

<iframe allowfullscreen sandbox="allow-top-navigation allow-scripts" width="400" height="400" frameBorder="0" src="https://www.mastofeed.com/apiv2/feed?userurl=https%3A%2F%2Fmastodon.social%2Fusers%2FAndreasZeller&theme=light&size=80&header=false&replies=false&boosts=false"></iframe>

<!--
## Latest News from [@AndreasZeller](https://twitter.com/AndreasZeller)

<a class="twitter-timeline" data-lang="en" data-height="300"  data-chrome="noheader nofooter noborders transparent"
href="https://twitter.com/AndreasZeller" data-dnt="true">Tweets by AndreasZeller</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<small>(also available via <a href="https://mastodon.social/@AndreasZeller" rel="me">@AndreasZeller@mastodon.social</a>)</small>
-->


## Current Projects

Our **research projects** involve generating software tests, automated debugging and repair, analyzing mobile systems, analyzing user interfaces, and more. Essentially, our research focuses on the following questions:

* How can we systematically test complex software systems?
* How can we accurately determine and characterize input formats?
* How can we explain causes and circumstances of software failures?

Our **solutions** typically apply and combine several techniques including dynamic analysis, static analysis, specification mining, test generation, natural language processing, machine learning, constraint solving, and formal languages:

* My largest project in 2020 was [The Fuzzing Book](https://www.fuzzingbook.org/)&mdash;an interactive textbook on test generation ("fuzzing") techniques.  You can execute and edit the code right in your browser.
* In 2021, my [Debugging Book](https://www.debuggingbook.org/)  presented and implemented techniques for automated debugging and repair.
* In 2022 and beyond, our projects will focus on semantic fuzzing and debugging, centered around our all-new [ISLa specification language and input generator](https://rindphi.github.io/isla/).


## Current Papers

My papers can be found on [Google Scholar](https://scholar.google.com/citations?user=-Qytr_YAAAAJ&hl=en&oi=ao), in the [ACM Digital Library](https://dl.acm.org/profile/81100307506), and in [DBLP](https://dblp.uni-trier.de/pers/z/Zeller:Andreas.html). For recent works and preprints, check out my [CISPA publication list](https://cispa.de/people/zeller/).


## My Courses

* In Winter 2022/23, we offer our advanced course on automated debugging, based on [The Debugging Book](https://www.debuggingbook.org/).
* In Summer 2023, we plan to offer our advanced course on security testing, based on [The Fuzzing Book](https://www.fuzzingbook.org/).

Every semester, we also offer [seminars and proseminars around automated testing and debugging](https://cms.cispa.saarland/).

Check out our courses [here](https://cms.cispa.saarland/).


## My Group

At CISPA and Saarland University, I work with great students and Post-Docs from across the world on cutting-edge research:

* [Dr.&nbsp;Dominic Steinhöfel](https://www.dominic-steinhoefel.de) (Post-Doc)
* [Leon Bettscheider](https://cispa.de/de/people/leon.bettscheider) (Ph.D. student)
* [Martin Eberlein](https://cispa.de/de/people/c01maeb) (visiting Ph.D. student from HU Berlin)
* Max Eisele (Ph.D. student @ Bosch)
* [Johannes Lampel](https://cispa.de/de/people/johannes.lampel) (Ph.D. student @ Microsoft)
* [Tural Mammadov](https://cispa.de/en/people/c01tuma) (Ph.D. student)
* [Michaël Mera](https://cispa.de/people/michael.mera/) (Ph.D. student)
* [Marius Smytzek](https://cispa.de/de/people/marius.smytzek) (Ph.D. student)
* Fengmin "Paul" Zhu (Ph.D. student)

We are constantly looking out for great students and Postdocs.  Our positions are well-paid and allow for highly productive research.  If you are interested in a Ph.D. or Postdoc position, please [apply at CISPA](https://www.cispa.de/) and state your specific interests.

Here is a list of [former group members](Group.html).


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

[Follow me on Mastodon](https://mastodon.social/@AndreasZeller) to stay updated about current work and relevant events.

<small>I do not collect any data from this site, but GitHub may do. See the <a href="https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement">GitHub Privacy Statement</a>
for details</small>.