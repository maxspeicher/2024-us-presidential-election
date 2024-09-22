# Max's 2024 U.S. Presidential Election Predictions

## September 22, 2024

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
