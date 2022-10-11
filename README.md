# coupon_redemption
First practical assignment - exploring factors impacting coffee house coupon redemption rates.
Full Jupyter notebook with detailed analysis can be found here: https://github.com/eyfeldb/coupon_redemption/blob/main/prompt.ipynb

<br /> Based on the initial data analysis we have identified that none of the numerical variables present in the data have a meaningful impact on 'coffee house' coupon redemption rates - these variables include age, temperature, children, direction or distance to the redemption place. 
<br /> These findings (especially distance or direction) make sense in the context of variables we DO see having an impact on redemption rates. 

<br /> First of all, redemption of coffee house coupon depends significantly on whether someone has been to a coffee house at least once a month. Although higher frequency has marginal impact on subsequent increases in redemption rates.

<br />Time of day has another major impact and is directly connected with the destination of the customer. Specifically, 10AM and 2PM  timeslots where customers's destination is "no urgent place" have 15% to 20% higher redemption rate in absolute terms vs. other time slots

<br /> Having company (friends or kids) on these rides (10am/2pm leisure drives) has a further positive impact on redemption rate (~7%-9% improvement)

<br /> We've also identified that occupation is another factor correlating to redemption rates for coffe house coupons with healthcare and building/cleaning/maintenance workers being most likely to redeem the coupons. Interestingly enough, while these groups also have highest redemption rate during 10am and 2pm timeslots, they are also much more likely to redeem at 7AM compared to the general population (72% vs 44% respectively).

<br /> Overall, we obverve that existing dataset has multiple descriptive characteristics that can reasonably well help identify groups that are more likely to redeem coffee house coupons. In the short term, targeting coffee house coupons during 10am / 2pm time slots and focusing on top occupations will likely maximize redemption rates (as we don't necessarily have a way of knowing how many passangers customers have).
<br />    Additionally, there are likely additional groups we haven't identified as part of the initial analysis that are also more likely to redeem the coupon. In the long term we recommend building out a proper ML model to identify specific customer cohorts based on combination of key variables for even better targeting and broadening the customer base without compromising redemption rates.



