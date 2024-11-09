---
layout: post
title:  "Tire Factory Fire in Daejeon and Air Pollution Exposure of Local Residents"
date:   2024-10-23 20:21:00
image:  /20241023_tirefire/1_tirefire_fstation.jpg
tags: Thoughts Research
lang: en
permalink: /en/2024/10/23/tirefactory/
related_ko: /ko/2024/10/23/tirefactory/
---

##### Tire Factory Fire in Daejeon

<img src="{{site.baseurl}}/images/20241023_tirefire/1_tirefire_fstation.jpg" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>

On March 12, 2023, at 10:09 PM, a fire broke out at the Hankook Tire factory in Daejeon, South Korea. The fire lasted 58 hours, completely destroying the second plant and consuming 210,000 tires [[News article 1]](https://v.daum.net/v/20230313141529622){:target="\_blank"}. The above photo (provided by the Daejeon Fire Department) and a [news video](https://www.youtube.com/embed/yWlLCndulLc?start=51){:target="\_blank"} from the morning of the 13th give us an idea of the fire's severity at that time.<br>

<img src="{{site.baseurl}}/images/20241023_tirefire/2_tirefire_NARA.png" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>

<p style="text-align: center; color: #808080; font-size: 14px;">

Satellite image from 10:00 AM on March 13, 2023

</p>

The above satellite image, taken at 10:00 AM on March 13, 2023, was provided by Nara Space, a satellite startup. As can be seen in the image, smoke from the fire at the factory spread to nearby areas. As reported in [[News article 2]](https://v.daum.net/v/8JgUAhEQz6){:target="\_blank"}, large residential complexes are located around the factory. Thus, it is likely that residents of these areas experienced respiratory issues from direct smoke exposure and anxiety due to the sudden fire disaster. <br><br>

##### Government Investigation on Air Pollution Exposure from the Fire

The local government of Daedeok-gu, where the factory is located, announced on March 17, 2023, that there were no notable findings in air and water quality tests conducted in the vicinity following the fire [[News article 3]](https://v.daum.net/v/20230317180928236){:target="\_blank"}. According to the report, air quality was monitored at a nearby apartment using mobile measurement equipment for 24 hours starting at midnight on the 16th, measuring pollutants like sulfur dioxide, particulate matter, benzene, and others, all of which reportedly did not exceed standards.

<img src="{{site.baseurl}}/images/20241023_tirefire/3_tirefire_report.png" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>

<p style="text-align: center; color: #808080; font-size: 14px;">

Air quality measurement report from Daejeon City Health and Environment Research Institute

</p>

The above is part of the air quality monitoring results provided by the Fine Dust Analysis Department of the [[Daejeon City Health and Environment Research Institute]](https://www.daejeon.go.kr/hea/index.do){:target="\_blank"}. Air quality was monitored over 13 days, longer than mentioned in [[News article 3]](https://v.daum.net/v/20230317180928236){:target="\_blank"}, and no significant differences were observed between measurements at the mobile station and other stations in Daejeon. With no follow-up reports, it appears that no additional measures were taken after the fire.<br>

However, the mobile monitoring station was located in Geumgang Exelu Tower Apartments, approximately the same distance from the Hankook Tire factory as the Munpyeong-dong monitoring station. So comparing these two values may not be meaningful [[Related Map 1]](https://map.naver.com/p/search/%EA%B8%88%EA%B0%95%EC%97%91%EC%8A%AC%EB%A3%A8%ED%83%80%EC%9B%8C%EC%95%84%ED%8C%8C%ED%8A%B8?c=15.82,0,0,0,dh){:target="\_blank"}. Instead, Munpyeong-dong station, located 500 meters from the factory, could better represent air pollution levels resulting from the fire. When focusing on the highest recorded levels in the report, PM<sub>10</sub> at the mobile unit and Munpyeong-dong station were 304 µg/m³ and 299 µg/m³ respectively, both of which are over 60 µg/m³ higher than the urban air quality average of Daejeon. PM<sub>2.5</sub> levels show a similar trend, with values of 84 µg/m³ and 133 µg/m³ at the mobile unit and adjacent station, respectively, both exceeding the urban air quality average of 63 µg/m³ by 20–50 µg/m³. Even short-term exposure to high particulate matter levels can have lasting respiratory impacts [[Related Study 1]](https://www.sciencedirect.com/science/article/pii/S0269749123011259){:target="\_blank"}, and a 10 µg/m³ increase in daily PM exposure is associated with a 0.7% increase in daily mortality [[Related Study 2]](https://www.nejm.org/doi/full/10.1056/NEJMoa1817364){:target="\_blank"}. <br><br>

##### Estimating Air Pollution Exposure of Local Residents from the Fire

##### Simple Comparison Between Monitoring Stations

<img src="{{site.baseurl}}/images/20241023_tirefire/4_tirefire_djmap.png" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>

<p style="text-align: center; color: #808080; font-size: 14px;">

Location of air pollution monitoring stations in Daejeon, Station 1: Munpyeong-dong station, with residential buildings in blue on the right

</p>

How much additional air pollution were local residents exposed to due to the fire? As explained earlier, one government air pollution monitoring station in Daejeon (Munpyeong-dong station) is located near the factory. By simply comparing air pollution measurements from Munpyeong-dong station to those from other Daejeon stations, we can estimate the degree of excess exposure in the area. Hourly data from air pollution monitoring stations in Daejeon was obtained from the [[AirKorea website]](https://www.airkorea.or.kr/web/){:target="\_blank"} and plotted as a time series below. The time series shows that after the fire, Munpyeong-dong station recorded rapid increases in concentrations, especially for PM<sub>2.5</sub>, PM<sub>10</sub>, SO<sub>2</sub>, and CO. Additionally, there were many missing values at Munpyeong-dong station immediately after the fire on March 13–14. While AirKorea and the National Institute of Environmental Research did not provide further explanation for the missing values, it is reasonable to assume that the high levels of air pollution from the fire could have caused errors in measurements.

<br>

<img src="{{site.baseurl}}/images/20241023_tirefire/5_tirefire_monitor.png" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>

<p style="text-align: center; color: #808080; font-size: 14px;">

Hourly air pollution levels before and after the tire factory fire

</p>

<br>

###### Estimation Using Generalized Synthetic Control Method

The Generalized Synthetic Control Method is a useful statistical analysis technique for assessing the impact of sudden events or policies in society [[Related Study 3]](https://journals.lww.com/epidem/abstract/2022/11000/using_the_generalized_synthetic_control_method_to.4.aspx){:target="\_blank"}. For example, let's assume a new environmental policy aimed at improving air quality was implemented in City A, and we want to evaluate the policy's effectiveness. To do so, we would compare air pollution levels in City A after the policy implementation with the levels that would have been observed in a counterfactual scenario without the policy. However, since the policy has already been implemented in City A, we cannot directly observe these counterfactual values.

Thus, we typically use data from other cities (control cities) where the policy was not implemented to make comparisons with City A. Ideally, we would compare City A with cities that have similar characteristics (e.g., population, infrastructure), confirmed by similar air pollution levels and patterns before the policy. However, finding other cities with air quality trends identical to City A’s can be challenging.

This is where the Generalized Synthetic Control Method comes in. This method synthesizes data from several control cities to create a 'synthetic city' that closely resembles City A. The air pollution levels in this 'synthetic city' represent what would have been observed in City A under a no-policy scenario, allowing us to evaluate the policy’s effectiveness by comparing the air pollution levels between City A and the synthetic city.

In the case of the tire factory fire in Daejeon, we can apply this analysis method by treating the Munpyeong-dong station, located near the fire, as City A, and the other 10 air pollution monitoring stations in Daejeon as the control cities to create the synthetic control. We synthesized the synthetic control using daily air pollution data from January 1, 2023, to March 12, 2023, and compared air pollution levels between Munpyeong-dong station and the synthetic control group over the 3 days of the fire (March 13–15, 2023) and the 10 days following the fire (March 13–22, 2023). <br><br>

<img src="{{site.baseurl}}/images/20241023_tirefire/6_tirefire_gsynth_ap.jpg" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>
<p style="text-align: center; color: #808080; font-size: 14px;">
Daily air pollution levels before and after the tire factory fire, exposed: Munpyeong-dong station, control: synthetic control </p>

<img src="{{site.baseurl}}/images/20241023_tirefire/7_tirefire_gsynth_ap_table.png" style="width: 100%; height: auto; display: block; margin: 0 auto;"/>
<p style="text-align: center; color: #808080; font-size: 14px;">
Estimated excess air pollution concentrations observed at Munpyeong-dong station before and after the tire factory fire </p>
<br>

The analysis results indicate that during the period before the fire was fully contained (0-2 days after the fire started), PM<sub>2.5</sub> concentrations at Munpyeong-dong station exceeded those of other stations by 29.8 µg/m³, PM<sub>10</sub> by 81.5 µg/m³, NO<sub>2</sub> by 12.6 ppb, SO<sub>2</sub> by 22.3 ppb, and CO by 0.5 ppm. Over the 10 days following the fire, Munpyeong-dong station recorded excess concentrations of 125.2 µg/m³ for PM<sub>10</sub>, 50.4 ppb for NO<sub>2</sub>, 32.0 ppb for SO<sub>2</sub>, and 0.5 ppm for CO. These findings suggest that, at a minimum, residents living near Munpyeong-dong station experienced excess exposure to air pollution from the Hankook Tire factory fire compared to residents in other areas of Daejeon. <br><br>

##### Summary
* The Hankook Tire factory fire, which broke out at 10:00 PM on March 12, 2023, lasted for 58 hours.
* Residents living near the Hankook Tire factory may have been affected by air pollution caused by the fire.
* Comparison between air pollution levels at the Munpyeong-dong station (500 meters from the factory) and other monitoring stations in Daejeon, using a synthetic control analysis, showed excess exposure to PM<sub>10</sub>, NO<sub>2</sub>, SO<sub>2</sub>, and CO over 10 days following the fire.
* It is likely that at least residents near Munpyeong-dong station were exposed to excess air pollution due to the fire, potentially resulting in adverse health effects. 

<br>
##### Related Paper
For further details, refer to this [[Paper]](https://ehp.niehs.nih.gov/doi/epdf/10.1289/EHP14115){:target="\_blank"}.

Han, C., Jang, M., Yoon, J., Lee, B., Kim, J., Jang, H., & Benmarhnia, T. (2024). Estimating the acute health effects of smoke exposure from an urban factory fire accident: a case study of a tire factory fire in Korea. Environmental Health Perspectives, 132(8), 087008. <br><br>

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).



<style>
/* 본문 및 헤딩에서 자연스러운 줄바꿈 설정 */
body, p, h1, h2, h3, h4, h5, h6 {
    word-break: keep-all;
    line-break: auto;
}

/* 제목(h1) 왼쪽 정렬 */
h1.post-title, .post h1 {
    text-align: left !important;
}
</style>
