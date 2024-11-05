# Max's 2024 U.S. Presidential Election Predictions

## Final Predictions (morning of November 5, 2024)

👇🏻 Check the first update from September 22 for [details on methodology](#september-22-2024).

### Based on Weighted High-Quality Polls

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 **Kamala Harris** | **271** 🏆    | **54%**           |
| 🔴 Donald Trump      | 267          | 44%               |

<img width="695" alt="image" src="https://github.com/user-attachments/assets/da1ae791-2bad-4e7e-97ba-5e5a6a04a6a4">


### Adjusted by Full 2016/20 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 Kamala Harris     | 252          | 14%               |
| 🔴 **Donald Trump**  | **286** 🏆    | **85%**           |

<img width="699" alt="image" src="https://github.com/user-attachments/assets/a0dcaad0-3e30-4b96-843a-ae885b76f67c">


### Adjusted by Half 2016/20 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 Kamala Harris     | 259          | 27%               |
| 🔴 **Donald Trump**  | **279** 🏆    | **72%**           |

<img width="721" alt="image" src="https://github.com/user-attachments/assets/de8718f8-192e-4dd5-a6bb-cd312596db70">


### Adjusted by 2012 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 **Kamala Harris** | **279** 🏆    | **71%**           |
| 🔴 Donald Trump      | 259          | 28%               |

<img width="696" alt="image" src="https://github.com/user-attachments/assets/6843b54f-262a-4136-b02c-7420930ef6e3">


### Adjusted by 2022 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 **Kamala Harris** | **275** 🏆    | **68%**           |
| 🔴 Donald Trump      | 263          | 32%               |

<img width="696" alt="image" src="https://github.com/user-attachments/assets/d6f374fa-7e07-4307-a31d-19b52357ee0d">


## Monte Carlo Simulation

You can find the latest simulations for calculating the chances of winning the election at https://colab.research.google.com/drive/1XOjITUeGjyDmC1fe3c27AmkbuYbaSZEy?usp=sharing or in the `monte_carlo` folder.


## Updates

I also post regular updates on Twitter (now 𝕏): https://twitter.com/maxspeicher

And I've discovered Bluesky: https://maxspeicher.bsky.social/

### November 2, 2024: Election Forecasts, Schmelection Forecasts

**What if pollsters are just too afraid of Trump this time around?**

Out of curiosity about the data-science side of things, in September, I started my [own little forecast](https://github.com/maxspeicher/2024-us-presidential-election) for the 2024 U.S. presidential election, which considers three different scenarios: ① based on weighted high-quality polls only; ② adjusted by the average polling bias from 2016/20; and ③ adjusted by just **half** the 2016/20 bias. I’ve previously written about my methodology and predictions [here](https://hackernoon.com/the-polls-are-looking-good-for-harris-with-the-201620-polling-error-shes-in-trouble-as-of-now) and [here](https://hackernoon.com/polling-error-or-no-polling-error-the-truth-will-probably-lie-somewhere-in-the-middle).

In the latter article, I lay out why I believe another polling bias underestimating Trump is a very real—even probable—possibility that can’t be dismissed. Trump as a candidate seems to completely defy the laws of “normal” elections. It’s unclear how much pollsters have understood and fixed the reasons for their misses in the past 2 elections; the “shy Trump voter” might still exist. On top, Republican-initiated voter suppression—like purging voters from voter rolls in Virginia this close to an election, as [recently allowed by the Supreme Court](https://www.npr.org/2024/10/30/g-s1-30644/supreme-court-virginia-elections)—will disadvantage Democrats in at least some places, which can’t be captured by opinion polling.

In the past weeks, however, I’ve also seen arguments as to why things could be the other way ‘round this time, and I must admit that I find some of them quite convincing.

[Mason McCann argues](https://twitter.com/__Guntar__/status/1851339376196010260) around campaign-related fundamentals and that Harris has an advantage in every single one of them: money, ground game, vibe, you name it. And it’s true that it seems the Trump campaign can’t really keep up with these. While my take has been that this election is probably most similar to 2016/20 (based on the assumption that you can’t compare elections involving Trump to “normal” elections), McCann argues it might actually be closer to 2012 due to certain similarities: an “enthusiastic” campaign, “perceptions of a bad economy,” and a “very overconfident republican campaign,” among others. Finally, he makes the point that 2024 is different from 2016/20 in that HRC simply didn’t do a lot of campaigning in the rust belt and in 2020, there was no GOTV ground game due to Covid, which, of course, looks **very** different this year.

So, campaign-related fundamentals point to Harris, and admittedly, this is hard to capture in a purely polling-based forecast. If Dems manage to get their supporters to vote in bigger numbers than in 2016/20—and observations so far suggest this—there might be “a mild surprise when the electorate is not as GOP as the pollsters assume,” [writes Dan Guild](https://twitter.com/dcg1114/status/1851779439899578606). “Pollsters consistently assume a very Republican electorate—my guess is to avoid ’16/’20.”

Nate Cohn admits as much in [his latest article](https://www.nytimes.com/2024/11/01/upshot/so-can-we-trust-the-polls.html). And @Angry_Staffer, based on this, [writes](https://twitter.com/Angry_Staffer/status/1852421106155540596): “Basically, pollsters are terrified of being wrong again, so they’re flat-out ignoring ‘very blue’ results.”

So, just for funsies, let’s take a look at the case that this year will play out like 2012, shall we? Luckily, Prof. Jacob Long has done a fantastic job [analyzing and providing past polling biases on his blog](https://jacob-long.com/post/polling-errors-map-24/), and that’s what I’ll be working with. I’ll just add the point estimate for the bias to my own polling averages without adjusting the standard deviation. Simply to get a quick, general idea in which direction this would move the forecast. We’re all just 🔮ing here anyway.

As a reminder, this is what my current prediction based on weighted high-quality polls only looks like. Michigan, Nevada, North Carolina, and Pennsylvania are toss-ups (according to 538’s definition). Overall, Harris is the ever so slight favorite.

<img width="772" alt="image" src="https://github.com/user-attachments/assets/911c9be0-a0b6-481f-9cf1-7c225e408b13">

And when we adjust by the 2012 polling bias, we get this:

<img width="772" alt="image" src="https://github.com/user-attachments/assets/ecd49edc-8237-4d72-bc3b-ff763291f9a0">

This would look a lot better for Democrats, but it’s still a relatively close race. Georgia is a toss-up now while Harris has much more comfortable chances in Michigan and Nevada. I’ve also run [my Monte Carlo simulation](https://colab.research.google.com/drive/1XOjITUeGjyDmC1fe3c27AmkbuYbaSZEy?usp=sharing) with these probabilities:

```
④ With 2012 polling bias
===============================
Harris's probability of winning: 71.38%
Trump's probability of winning: 28.20%
Probability of tie: 0.41%
```

While we’re at it, let’s also have a look at how the 2022 polling bias—from the most recent and first “post-Covid” election—would change the predictions:

<img width="774" alt="image" src="https://github.com/user-attachments/assets/7c143004-5db5-4e28-ad96-de92fca7c7de">

Most significantly here, Michigan, Pennsylvania, and Wisconsin are now lean or likely D. And these are also the ones where Harris is the favorite in all three of the above scenarios. Chances of winning with the 2022 polling bias:

```
⑤ With 2022 polling bias
===============================
Harris's probability of winning: 66.56%
Trump's probability of winning: 33.10%
Probability of tie: 0.34%
```

So, what are we gonna do with this now? What’s **the** prediction? Who has the better chances of winning the election, and how good are they? I have no clue whatsoever. As I already said above, it’s all 🔮ing at this point in time. There are so many variables in this, so many things that could go one or the other way … What we can do at best is think about which scenarios are maybe a bit more likely than others. My opinion on this: Accurate polls (①) and the same polling bias as in 2016/20 (②) are rather unlikely. Which leaves ③ (half 2016/20 bias), ④ (2012 bias), and ⑤ (2022 bias) as the more likely of my scenarios.

In any case, the election is gonna happen, there’ll be a winner, and there’ll be one option that was closer than the others. All we need is just a little more patience.


### November 1, 2024

It's getting really tight. The latest batch of polls has been a good one for Trump.

① If the high-quality polls are correct, Harris is the slight favorite, but well ... flip a coin. As far as the Democrats are concerned, there's barely any room for a polling bias underestimating Trump if they want to have a half-decent shot at winning. Again, _if_ we wanna believe the polls ...

<img width="695" alt="image" src="https://github.com/user-attachments/assets/9216b075-0a29-496f-9864-191d7d211ef9">

② If the polling bias will be similar to 2016/20, it's probably a done deal for Trump.

<img width="695" alt="image" src="https://github.com/user-attachments/assets/7fc9ced9-74da-480e-9a74-03c31b8b2bf2">

③ Even with just half the polling bias from 2016/20, he's the favorite in all swing states.

<img width="697" alt="image" src="https://github.com/user-attachments/assets/6ca310c7-a6c9-4ced-936f-4f9b239b0b82">

Correspondingly, the chances of winning the election look like this for the three scenarios:

```
① Weighted high-quality polls
==============================
Harris's probability of winning: 55.07%
Trump's probability of winning: 43.82%
Probability of tie: 1.10%

② With full 2016/20 polling error
==============================
Harris's probability of winning: 13.94%
Trump's probability of winning: 84.95%
Probability of tie: 1.11%

③ With half 2016/20 polling error
==============================
Harris's probability of winning: 27.34%
Trump's probability of winning: 71.46%
Probability of tie: 1.20%
```


### October 24, 2024

There's still barely any movement and the race has seemingly stalled.

① No changes in expected EVs for each candidate based on high-quality polling:

<img width="695" alt="image" src="https://github.com/user-attachments/assets/79b15253-1c56-4624-a615-ec7e0cfb7e4a">

② Same when adjusting for the average 2016/20 polling error – no gains or losses in expected EVs despite some slight changes in probabilities:

<img width="695" alt="image" src="https://github.com/user-attachments/assets/92718dc4-0d38-4977-a2d8-2d32bdfa75af">

③ The only noticeable change: Compared to one week ago, Trump gains 1 expected EV in the scenario with a half 2016/20 polling error:

<img width="698" alt="image" src="https://github.com/user-attachments/assets/9bba3f41-17ca-4562-a5da-2a418ea742d0">

What I'll be adding from now on are each candidate's chances of winning the entire election. Together with the expected EVs, this should give a relatively complete picture. I'm calculating those chances using a Monte Carlo simulation in which I simulate the election in the 7 swing states a total of 1000000 times. You can find the code at https://colab.research.google.com/drive/1XOjITUeGjyDmC1fe3c27AmkbuYbaSZEy?usp=sharing, and I'll also upload the `.ipynb` and `.py` files here.

```
① Weighted high-quality polls
===============================
Harris's probability of winning: 59.10%
Trump's probability of winning: 39.71%
Probability of tie: 1.19%

② With full 2016/20 polling error
===============================
Harris's probability of winning: 16.72%
Trump's probability of winning: 82.06%
Probability of tie: 1.23%

③ With half 2016/20 polling error
===============================
Harris's probability of winning: 31.67%
Trump's probability of winning: 67.01%
Probability of tie: 1.32%
```


### October 17, 2024

The latest state of the race. An ever so slight shift to Trump, but virtually nothing has changed over the past week.

① Weighted high-quality polls only:

<img width="750" alt="image" src="https://github.com/user-attachments/assets/e3ee38b5-aa4e-498f-9adc-8fc3f73be260">

② Adjusted by full average polling error from 2016/20:

<img width="754" alt="image" src="https://github.com/user-attachments/assets/43808f09-2748-4423-8a99-2c46593b1b39">

③ Adjusted by half average polling error from 2016/20:

<img width="753" alt="image" src="https://github.com/user-attachments/assets/623db1bb-e728-4a9a-b2d5-ab7fb2557b47">


### October 9, 2024

**Polling Error or No Polling Error? The Truth Will Probably Lie Somewhere in the Middle (Which Still Doesn’t Look Very Good for Harris)**

So far, in my own little forecast for the 2024 U.S. presidential election, I've produced two predictions:

① One purely based on a weighted average of high-quality 2024 polling.<br />
② The above, but corrected by the average of the 2016/20 polling error.

(Please see [below](https://github.com/maxspeicher/2024-us-presidential-election?tab=readme-ov-file#september-22-2024) for details.)

From now on, I'm going to include a third one, assuming this year's polling error will only be **half** of the 2016/20 average error. Let me elaborate.

It's most probably just as unrealistic to assume there'll be negligible systematic polling error in the swing states this year (①) as to assume it'll be as big as in 2016/20 (②). The truth will most probably lie somewhere in the middle.

Pollsters have been busy identifying reasons for their previous misses & finding potential fixes (https://abcnews.go.com/538/polling-broken-pollsters-face-trump-era-challenges/story). For instance, to tackle nonresponse bias & challenges in identifying likely voters, they increasingly rely on mixed modes to contact participants & have improved weighting based on the 2020 vote preferences of respondents. Hence, it's unlikely the polling error in 2024 will be as extensive as before.

However, it's equally unlikely it'll all but disappear. While pollsters do have a good understanding of what probably caused polling errors in 2016/20, it's unclear if their adjustments will be effective. On top, there are efforts to make it harder for certain groups to vote, virtually all of which are carried out by Republicans (cf. https://www.democracydocket.com/). For instance, the RNC sued to remove thousands of registered voters in AZ, MI, NC, & NV (https://x.com/MuellerSheWrote/status/1837886286541279307). Also, there has been a deliberate reduction in polling places, often in predominantly black areas (https://civilrights.org/democracy-diverted/). Here, as well, the question is how effective these measures will be. But it's safe to assume there'll be people who participated in opinion polling with the intent to vote & then won't (be able to).

Therefore, as already said, the truth will most probably lie somewhere in the middle. Ergo: a 3ʳᵈ prediction with half the polling error from the two previous election cycles. I've also adjusted one more thing in all predictions: as Pew Research explains, opinion polls' "real margin of error is often about double the one reported" (https://www.pewresearch.org/short-reads/2024/08/28/key-things-to-know-about-us-election-polling-in-2024/). Hence, I'm multiplying all standard deviations by 2 now.

Alright, now—finally!—for my latest forecast.

① Here's the state of the race based on weighted high-quality polls only:

![image](https://github.com/user-attachments/assets/b272efea-54bc-4605-9447-ea054ab3eec8)

② When adjusted by the full average polling error from 2016/20:

![image](https://github.com/user-attachments/assets/9c4274e0-5736-4619-93ed-bbcb2b399657)

③ And with just half the average polling error from 2016/20:

![image](https://github.com/user-attachments/assets/415e1931-885e-4ade-a5fc-9c3303c0596e)

(Link to post: https://twitter.com/maxspeicher/status/1844182045335179607)


### October 1, 2024

The most recent predictions include new polls from ABC News/Washington Post, Quinnipiac University, and Emerson College in AZ, GA, and NC. And things seem to be shifting in the opposite direction again. I'm also using an unbiased estimator for the calculation of the weighted standard deviation of the polling error now, for a more precise inference (cf. http://re-design.dimiter.eu/?p=290).

Weighted polls only:

<img width="693" alt="image" src="https://github.com/user-attachments/assets/6d7a85ec-52bc-47cd-b377-e33abf8ca312">

After adjusting for polling error:

<img width="692" alt="image" src="https://github.com/user-attachments/assets/4aeec3a4-649b-4e4d-9ea3-2b506efb6f28">


### September 27, 2024

The latest batch of polls from Marist College, Beacon Research/Shaw & Co. Research, and YouGov has been good for Harris. She's gaining 3 expected EVs in the weighted polls–only prediction:

<img width="694" alt="image" src="https://github.com/user-attachments/assets/ad0755fa-0d30-4404-acf1-afb1043ef5ef">

... and 2 expected EVs when adjusting for polling error:

<img width="694" alt="image" src="https://github.com/user-attachments/assets/780da5f6-a29e-4ebe-b8da-a989fd7cd864">


### September 24, 2024

I added the latest NYT/Siena polls that ran from Sep 17–21. Also, based on the probabilities for each candidate, my predictions now include expected electoral votes (EVs). This is what it looks like purely based on the weighted 2024 polling (see methodology below):

![image](https://github.com/user-attachments/assets/1e135330-1ec5-4a59-8121-d28975fb1f31)

And these are the expected EVs when adjusting based on the averaged 2016/20 polling error:

![image](https://github.com/user-attachments/assets/f5f2f3a5-66cf-4f37-99cc-81f307c86a83)


### September 22, 2024

**The Polls Are Looking Good for Harris. With the 2016/20 Polling Error, She’s in Trouble as of Now.**

So, I've started playing around with [FiveThirtyEight's publicly available polling data](https://projects.fivethirtyeight.com/polls/president-general/2024/national/?ex_cid=abcpromo). Why? Because I'm kind of just interested in the polling around the #2024USPresidentialElection and was wondering how I would construct my own little prediction from scratch. So, here's what I did for a first try.

(Disclaimer: I'm not a professional data scientist. Playing around with the data and exploring some things is really my main focus.)

First and foremost, I want to keep it simple for now. As Kahneman explains in his book, “Noise”: Simple models often get the job done pretty well.

① Therefore, I only consider high-quality pollsters but without weighting their polls differently. I only include data points with a numeric_grade ≥2.5 (best: 3) in 538's dataset.

② What I do weight is closeness to election day. The closer to November 5 the more relevant the poll. I consider polls from up to 90 days (~3 months) before, weighted linearly. A poll ending on August 7 has a weight of 1/90, a poll ending on November 4 one of 90/90.

③ Lastly, I'm not looking at national polls. What I focus on are the 7 swing states that are going to decide the election.

With all this, we arrive at the following picture as of September 22. Harris in front in MI, NV, NC, PA, WI; Trump in AZ & GA.

![image](https://github.com/user-attachments/assets/020410b6-c8be-41ea-9b3c-def09a0401a1)

④ This, however doesn't take into account polling error, which was significant in both 2016 & 2020. So, I also did ①–③ for those two. I'm not considering elections before that because ever since Trump entered the stage, election dynamics have significantly changed. Old rules don't apply anymore. 2024 will be much more similar to 2020 & 2016 than to any election before that. The polling error for my methodology looks like this:

![image](https://github.com/user-attachments/assets/99aef61b-8542-4c00-99bc-f2c84c6588d0)

Following the “keep it simple” rule, let's assume the polling error in 2024 will be the average of 2016/20 and apply it to the margins from above, also adding the polling error uncertainty to the uncertainty from the polls:

![image](https://github.com/user-attachments/assets/39c4351b-5b04-4fbd-bb4c-07e9d5d5bfdb)

Now, one could argue that pollsters might have learned their lesson and polling will get more accurate again this year. This, however, was already an argument in 2020. Plus, at least part of the problem seems to be that certain Trump supporters simply don't want to participate in polls anymore due to trust issues (see, e.g., https://www.cnbc.com/2024/05/04/why-election-polls-were-wrong-in-2016-and-2020-and-whats-changing.html). Obviously, pollsters are trying to learn and adjust, but whether they'll be less of this year than in the two elections before, we'll only see on November 5. For now, I also don't take polling errors from 2022 elections into account. I have to read more on this first, and I assume that a presidential election is most similar to other presidential elections.

So, for this first try, my own little forecast includes one prediction purely based on weighted polls from high-quality pollsters, and one prediction assuming the 2024 polling error will be the average of 2016 & 2020.

(Link to post: https://twitter.com/maxspeicher/status/1837950963057152020)
