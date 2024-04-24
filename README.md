# What will happen with TikTok given the congressional ban?
- April 23, 2024

Now that the TikTok ban is on its way to Biden’s desk, you may ask: “Will ByteDance get this overturned in court?” “How much is TikTok US worth?” “Will Oracle and Walmart bid again?”

Google, ChatGPT, Perplexity, etc. have almost nothing to say on questions like these that involve judgment, uncertainty, modeling, and in-depth research. (Try it for yourself.)

[FutureSearch](https://github.com/varunaai) is a tool that answers hard questions like these by implementing the workflow of professional forecasts in software. We used it to analyze a variety of facets of the situation.

## Summary of findings

  - Biden will sign the Senate bill (>95%)

  - The Commerce Secretary will start the 12 month clock on TikTok (>95%)

  - TikTok will challenge the ruling (>95%), which may delay the clock starting to delist or divest, but they have only a ~20% chance to win

  - And if they lose, they will succeed in selling to a US company (75%)

  - The sale will be for $30-50B (CI 50%), assuming it does not include certain ByteDance IP

  - Walmart and Oracle won’t compete to buy it this time. Microsoft or Amazon are the top contenders, along with a consortium led by Susquehanna or Steven Mnuchin, possibly in partnership with Snap or X.

## Detailed findings

### Will TikTok win in its suit against the Department of Commerce?

The first three points are well established by public statements from Biden, TikTok execs. The first complicated question is whether TikTok will prevail when it sues the Department of Commerce to get the ruling overturned. Our analysis is in [Probability TikTok will win a lawsuit that prevents the U.S. government from forcing a divestiture or banning its operations in the U.S.](https://app.futuresearch.ai/forecasts/ZYMek/public)

Courts have struck down bans like this on First Amendment grounds:
[image]

But the most similar cases to TikTok's forthcoming suit rarely succeed. ByteDance prevailed against Trump in 2020, but that was an executive order, not congressional legislation. Tencent, Huawei, ZTE, China Telecom, China Mobile International, Sberbank of Russia, have all lost in similar suits, given an overall estimate of a 13% historical success rate:
[image]

We also expect that the case will be heard by a DC District Court judge who is likely to side with Congress and the President, which could influence the ruling against TikTok. Still, overall we give TikTok a **20%** chance, higher than this 13%, as their case might be a lot stronger than the historical norm. Also, there are also other targets they could sue, other than the Department of Commerce.

### If they lose, will TikTok succeed in delisting or will they be forced to divest?

Our primary finding is that in the 5 most similar cases to what TikTok is facing, action from the CFIUS on national security grounds, in all 5 of them, the company managed to sell their US operations on time, instead of shutting them down:

[image]
*(You can interact with this widget here)[https://app.futuresearch.ai/forecasts/ZYMek/public#PAST]*

The most similar case is Grindr. One difference is that the Chinese company Kunlun didn't found Grindr, but did purchase it in 2018. In 2019, the CFIUS gave them until June 2020 to sell Grindr to a US company, citing national security concerns (presumably because it had information on the private sexual preferences of Americans, which could be very similar to how CFIUS sees TikTok). Kunlun did so, selling to San Vicente Acquisition for about $608.5 million.

Notably, this isn't all action under Trump. The same thing occurred in 2012 with Ralls Corporation, where the CFIUS required it to divest its US wind-farm project.

Finally, we predict there would be a huge political backlash if TikTok were in fact delisted from the Google and App stores. The app is used by half of all Americans under 30, so the motivation to find a deal of some kind will be very high.

https://app.futuresearch.ai/forecasts/ZYMek/public#PAST.

### If they sell, how much will it sell for?

Here, we are much less confident, giving this distribution:
[image]

The most important variable we find is whether TikTok US will include ByteDance's famous recommendation algorithm, or something similar to is. China has stated that this is proprietary and not for sale. TikTok US could presumably make a similar algorithm, or privately license it. How much of the value is in the algorithm vs. the userbase? We don't know, so this gives us a very wide confidence interval.

### Who will buy it?

This scenario, depending on all the above - the lawsuit, the price, the algorithm - is the most speculative. But we can reason about the potential buyers from their public statements, especially in how they conducted themselves when ByteDance prepared to sell TikTok US in 2020. We can also reason from the presumed very high price.

In 2020, Walmart and Oracle were the top contenders. TikTok US has in fact moved a lot of its compute to the Oracle Cloud. But we consider these two unlikely candidates, for financial reasons. TikTok US should be much more expensive this time, and Oracle's financial situation is much worse, having $87B in debt after some expensive acquisitions in 2021 and 2022. We don't find strong statements of interest from them.

At a higher price, Microsoft or Amazon are the top contenders. Microsoft did put in a bid in 2020, so we consider them the most likely of the big tech firms. Alphabet and Meta are struggling too much with antitrust to seriously consider this, plus they might expect such purcahses to be blocked by the FTC.

From public statements, a consortium led by Steve Mnuchin is the next most likely:

[image]

This "rebuilt in the US" attitude might require a large partnership of investors, similar to how Larry Ellison helped Elon Musk buy X. In fact, we see Snap or X as potential partners, even though their market caps might be lower than TikTok US, they could work in partnership with a network of investors. We don't feel confident enough to give probabilities here.

## Learn more

Learn more [here](https://github.com/varunaai) about the FutureSearch approach to answering these questions, or email us at beta@futuresearch.ai, and we’ll give out quota as capacity becomes available.

It searches for statements and historical actions of key people, like Steve Mnuchin, Biden, TikTok execs. That TikTok has a 20% chance to overturn this in court draws on a model where FutureSearch estimates only 13% of similar cases rule in favor of the company: https://app.futuresearch.ai/forecasts/Tn2Aa/public.

You can see more on our methods at https://github.com/varunaai. If you’d like to try it, email us at beta@futuresearch.ai, and we’ll give out quota as capacity becomes available.
