# Biden signs TikTok ban - what will happen next?
*April 24, 2024, [FutureSearch](https://futuresearch.ai)*

Biden just signed the Senate bill that forces ByteDance to sell or delist TikTok US. What will happen next? Will ByteDance get this overturned in court? How much is TikTok US worth? Will Oracle and Walmart bid again, or who else might buy it?

We researched this to provide the statements, facts, and historical precedent that best predict the outcomes.

## Summary of findings

  - Biden will sign the Senate bill (>95%)

  - The Commerce Secretary will start the 12 month clock on TikTok (>95%)

  - ByteDance will challenge the ruling (>95%), which may delay the clock starting to delist or divest, but they have only a ~20% chance to win

  - And if they lose, they will succeed in selling to a US company (75%)

  - The sale will be for $30-50B (CI 50%), assuming it does not include certain ByteDance IP

  - Walmart and Oracle won’t compete to buy it this time. Microsoft or Amazon are the top contenders, along with a consortium led by Susquehanna or Steven Mnuchin, possibly in partnership with Snap or X.

## Detailed findings

### Will TikTok win in its soon-to-come suit against the Department of Commerce?

Given their public statements, it's nearly certain that Biden will sign the bill, the Commerce Secretary will initiate the process to compel ByteDance to delist/divest TikTok US, and ByteDance will challenge the bill to get the ban overturned. So the first big question is, how can we infer whether ByteDance will prevail against the CFIUS and the Department of Commerce to get the ruling overturned?

First, we expect that the case will most likely be heard by a DC District Court judge. One likely candidate is Chief Judge James Boasberg, who is partial to Congress and the President:
![judge](/images/TikTok-judge.png)

That said, courts have struck down bans like this on First Amendment grounds:
![background](/images/TikTok-suit-background.png)
*[You can interact with this widget, and the below, on FutureSearch.](https://app.futuresearch.ai/forecasts/ZYMek/public)*

We also find that most similar cases to TikTok's forthcoming suit rarely succeed. ByteDance prevailed against Trump in 2020, but that was an executive order, not congressional legislation. Tencent, Huawei, ZTE, China Telecom, China Mobile International, Sberbank of Russia, have all lost in similar cases, given an overall estimate of a 13% historical success rate:
![model](/images/TikTok-suit-model.png)

Still, overall we give TikTok a **20%** chance, higher than this 13% statistic, as ByteDance's case might be a lot stronger than the historical norm.

### If they fail to overturn the ban, will TikTok succeed in divesting or will they be forced to delist from US app stores?

We find that in most similar cases to what TikTok is facing, action from the CFIUS on national security grounds, in all 5 instances, the company managed to sell their US operations on time, instead of shutting their US businesses down:

![divestment](/images/Divestment-model.png)

The most similar case is Grindr. One difference is that the Chinese company Kunlun didn't found Grindr, but purchased it in 2018. In 2019, the CFIUS gave them until June 2020 to sell Grindr to a US company, citing national security concerns (presumably because it had information on the private sexual preferences of Americans, which is similar to how CFIUS sees TikTok). Kunlun did so, selling to San Vicente Acquisition for ~$600 million.

Notably, this isn't all action under Trump. The same thing occurred in 2012 with Ralls Corporation, where the CFIUS required it to divest its US wind-farm project.

Finally, we predict there would be a huge political backlash if TikTok were in fact delisted from the Google and App stores. The app is used by half of all Americans under 30, so the motivation to find a deal of some kind will be very high.

The reasons they might fail relate to ByteDance IP, and the presumed very high price, as covered below.

### If they sell, how much will it sell for?

Here, we are much less confident, giving this distribution:
![distribution](/images/TikTok-sale-price.png)

The most important variable we find is whether TikTok US will include ByteDance's famous recommendation algorithm, or equivalent. China has stated that this is proprietary and not for sale. TikTok US could presumably make a similar algorithm, or privately license it. How much of the value is in the algorithm vs. the userbase? We don't know, so this gives us a very wide confidence interval.

### Who will buy it?

This scenario, depending on all the above - the lawsuit, the price, the algorithm - is the most speculative. But we can reason about the potential buyers from their public statements, especially in how they conducted themselves when ByteDance prepared to sell TikTok US in 2020. We can also reason from the presumed very high price.

In 2020, Walmart and Oracle were the top contenders. TikTok US has in fact moved a lot of its compute to the Oracle Cloud. But we consider these two unlikely candidates, for financial reasons. TikTok US should be much more expensive this time, and Oracle's financial situation is much worse, having $87B in debt after some expensive acquisitions in 2021 and 2022. We don't find strong statements of interest from them.

At a higher price, Microsoft or Amazon are the top contenders. Microsoft did put in a bid in 2020, so we consider them the most likely of the big tech firms. Alphabet and Meta are struggling too much with antitrust to seriously consider this, plus they might expect such purcahses to be blocked by the FTC.

From public statements, a consortium led by Steve Mnuchin is the next most likely:
![distribution](/images/Mnuchin-interest.png)

Steve Mnuchin has the unique background of being in the Trump cabinet during the 2020 executive order to divest TikTok, while also having career experience in investment and M&A. Mnuchin is seeking an AI partner to "rebuilt in the US", and he'll need to find investors. We see Snap or X as potential partners, even though their market caps might be lower than TikTok US, they could provide some of the capital and some of the AI expertise. 

## Learn more

Learn more [here](https://github.com/varunaai) about the FutureSearch approach to answering these questions. You can [request beta access](https://futuresearch.ai/futuresearch-beta-waitlist), or [request a demo](https://futuresearch.ai/request-a-demo).
