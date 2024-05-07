---
layout: post
title: "The transformation of New York City’s tap water lead contamination problem"
date: 2024-05-07
author: "Dongbo Hu, Yiming Liu"
---


![替代文本](/assets/image/NYC.webp)
### Introduction
<div style="text-align: justify;margin-bottom: 10px;">
Lead is a harmful metal that can have severe long-term effects on human health, even at trace levels. Studies have shown that exposure to lead not only profoundly affects the growth and development of children but also poses significant risks to adults, including increased blood pressure and problems with kidney and brain function. Crucially, even low levels can lead to health issues. Prolonged exposure to lead results in its accumulation in the body, and the longer the exposure, the more challenging it becomes for the body to eliminate the toxin. As most people with elevated blood lead levels do not look or feel sick, which can make lead poisoning hard to identify, lead poisoning remains a significant public health concern.
</div>

![替代文本](/assets/image/PP1.jpg)

However, as we find in the dataset of "NYC_EH_Data_Portal", between 2010 and 2012, about 2413 people living in New York aged 16 or older (a rate of 23 people per 100,000) had blood lead levels of 10 micrograms per deciliter or higher — the level the Centers for Disease Control and Prevention uses to define an elevated blood lead level for adults, which underscores lead exposure is a significant problem in that period of New York. What caused this? Is the situation in New York getting better now? Our analysis wants to do further exploration based on those two questions.

<iframe src="assets/image/lead_exposure_rates.html" height="400px" width="100%" style="border:none;" allowfullscreen="allowfullscreen">
  </iframe>
  
<div style="text-align: justify;margin-bottom: 10px;">
New York City’s water is delivered from upstate reservoirs through lead-free aqueducts and water mains. While the use of lead in household plumbing has been banned for decades, some older homes—particularly single family houses built in the 1910s through 1930s—may still have lead pipes and fixtures.  These pipes are now very old and, given their vast number and the complexity of the system, they are challenging to maintain and replace. Consequently, there is a significant risk that these aging pipes could lead to lead levels in the water supply exceeding safe standards. This situation could be one of the reasons why New York City had an elevated average annual lead rate(10 mg/L)  per 100000 people during the early 2010s.
</div>



<iframe src="assets/image/lead_concentration3.html" height="440px" width="100%" style="border:none;" allowfullscreen="allowfullscreen">
  </iframe>
<div style="text-align: justify;margin-bottom: 10px;">
According to the data in the figure, we can see that the annual average lead levels in 2014, 2015 and 2018 all exceeded the safety standard of 0.01 mg/L defined by the World Health Organization. This shows that New York City's water system does have safety risks when it comes to ensuring safe water quality. Especially when the old water supply system fails to be updated and upgraded in time, the safety of residents' drinking water still cannot be fully guaranteed.
</div>


### Geographical Analysis
<iframe src="assets/image/nyc_lead_levels_choropleth.html" height="440px" width="100%" style="border:none;" allowfullscreen="allowfullscreen">
  </iframe>
<div style="text-align: justify;margin-bottom: 10px;">
It can be clearly seen from the above geographical data map that the lead content in Queens, New York City, is much higher than other areas. The average lead level is 11.09 µg/l, which is significantly higher than other areas. This striking difference may be related to Queens-specific environmental factors. Queens is the largest borough in New York City, with a large population and numerous industrial facilities. Relatively poor infrastructure, especially aging water pipe systems and outdated industrial equipment, may be a major contributor to high lead levels in water. In addition, Queens’ large area and population density may complicate the challenges of water quality monitoring and pipeline renewal, increasing the difficulty of keeping water quality safe.
</div>


![替代文本](/assets/image/Lead_Concentration_Queens.png)
The graph above shows that lead levels in water began to decrease year by year from 2015 to 2019. This is good news and shows that the lead concentration in almost all samples in 2019 was below the safety threshold, reflecting a significant improvement in the quality of water bodies. It could be due to things like plumbing improvements or maintenance likeWe one treatment is adjusting the pH and by adding phosphoric acid, a common food additive, which forms a protective barrier on plumbing. However, what we can also see from the data as a potential problem is that the 2020 data shows a slight rebound in lead concentrations.


<iframe src="assets/image/lead_exposure_queens_20104.html" height="440px" width="100%" style="border:none;" allowfullscreen="allowfullscreen">
  </iframe>

<div style="text-align: justify;margin-bottom: 10px;">
According to the above graph, between 2010 and 2018, the annual average rate of blood lead levels exceeding 10 micrograms per deciliter per 100,000 people in Queens, New York, gradually decreased from 30.00 to 19.10. This shows that during these 8 years, the lead exposure problem in the area has been effectively controlled and the overall trend showed a decline, the rate of decline slowed between 2013 and 2015 and then stabilized. However, we still need to be wary of a potential rebound in lead levels in residents' blood, especially given that we do not have data after 2018 and the previous graph analysis shows that water quality data indicate that lead levels are gradually rising, so continued monitoring and prevention Measures are necessary.
</div>



### Conclusion
<div style="text-align: justify;margin-bottom: 10px;">
In summary, while New York City has made laudable progress in addressing lead contamination over the past few years, the process of comprehensive lead compliance continues, especially as lead levels in drinking water have rebounded in recent years. In addition to maintaining pipes, informing residents about the correct handling of lead in tap water is also a measure to artificially reduce lead levels. For instance, lead that is in household plumbing can dissolve into water, particularly when the water has not been used for several hours, so residents with lead plumbing can run the water from their tap until it turns noticeably colder before drinking it.
</div>

### Reference Link
<a href="https://www.nyc.gov/site/dep/water/lead-in-household-plumbing-faq.page"><sup>[1]NYC.gov</sup></a>

