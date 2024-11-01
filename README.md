# Max's 2024 U.S. Presidential Election Predictions

## Latest Predictions

👇🏻 Check the first update from September 22 for [details on methodology](#september-22-2024).

### Based on Weighted High-Quality Polls So Far

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 **Kamala Harris** | **271** 🏆    | **55%**           |
| 🔴 Donald Trump      | 267          | 44%               |

<img width="695" alt="image" src="https://github.com/user-attachments/assets/9216b075-0a29-496f-9864-191d7d211ef9">


### Adjusted by Full 2016/20 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 Kamala Harris     | 252          | 14%               |
| 🔴 **Donald Trump**  | **286** 🏆    | **85%**           |

<img width="695" alt="image" src="https://github.com/user-attachments/assets/7fc9ced9-74da-480e-9a74-03c31b8b2bf2">


### Adjusted by Half 2016/20 Polling Bias

| Candidate           | Expected EVs | Chance of Winning |
|---------------------|--------------|-------------------|
| 🔵 Kamala Harris     | 259          | 27%               |
| 🔴 **Donald Trump**  | **279** 🏆    | **71%**           |

<img width="697" alt="image" src="https://github.com/user-attachments/assets/6ca310c7-a6c9-4ced-936f-4f9b239b0b82">


## Monte Carlo Simulation

You can find the latest simulations for calculating the chances of winning the election at https://colab.research.google.com/drive/1XOjITUeGjyDmC1fe3c27AmkbuYbaSZEy?usp=sharing or in the `monte_carlo` folder.


## Updates

I also post regular updates on Twitter (now 𝕏): https://twitter.com/maxspeicher

And I've discovered Bluesky: https://maxspeicher.bsky.social/

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
