---
layout: post
title:  "From a technical issue to a new website"
date: 2016-09-01 00:00:00 +0800
categories: SeeChic
---

<center>
            <img src="https://lh3.googleusercontent.com/45jqsCNKQfh8WcFTRX667g9D4ZCqLxz21v-duLrBfT8Y-aJp1ityANWSQTjXogABbAdBOErM4VaR1gkqdjjEnlcAIk_M8j-w67bN5Yh7hQRvfXP4JNQmkiJ5s0yW-e0RdsIHd_1P8_miHYedQzXx5uc9x9i7_N71AoB5HZsL9DVL83Y_tQd-fbcHxXj5KqA6YsETtOKm4-0FaBMJXZk4HQEg2Lum-x8xb8npDqgs6H1B5dLKlZYA0Q-2wSkW-J7Grgl6a4GrP-axSnrD0TJUZAHZ56yy6hLyYpoK11b_jWkoiWj4O_USCixlhu-0Gu5eibjn0MqVRRcSsRIfaTvIADr6okAi6OUKk8rOocw16qtrojyN5Zxju44tm9KRdUQ3aC0cSERFL-Q2J2NQ64IEgc0kQ7G3eZJe231HdoUOdGaaSrAr5RgeQYcGkBNyGPtMnMoeUSskYXEPMJ4PI_OIuY0aO2jy3vKenzMqdWejBE1E-3Gh-WBi5knhu7VgI95fKYy0FRvQ4oMDlF-l-6TpgZBl91oHaX6hSmpaVJShEapLnLsONCRWbOnu5D8MBTYPXlJmVY1CmZ4IpHC3bK8uhyuuZck_qUD5x7L694AFCRoFsYEtttzt=w400-h150-no" width="40%" alt="SeeChic">
</center>

<i>SeeChic was a contact-lenses and sunglasses e-commerce platform in Singapore, created in April 2015. </i>

<h2>Problem</h2>

<p> Contact-lenses are very complex products to sell online, more complicated in term of technology and process than clothes or cosmetic. Given a contact-lense product “1 day acuvue moist for astigmatism” - on its own, this product has thousands of variants that depends on the customer prescription.  </p>

<p> Our problem was to provide real-time stock update on our website for more than 50,000 variants while using a CMS called Magento. In fact, the technology chosen to start was not the correct solution. Magento is a good solution for simple e-commerce business but it was not appropriate for our needs. </p>

<h2>How?</h2>

<strong>Analyse</strong>

<p>Once we took the decision that we needed a new technology for our e-commerce platform, we started to analyze our current customer behavior. For this, we’ve used mainly Google Analytics Conversion Funnel feature. Here are the differents scenarios that we’ve analyzed:</p>
<ul>
    <li>The completion of the prescription to the cart </li>
    <li>The sign-up in order to take an appointment with our optometrist</li>
    <li>From the landing on our website to the product page </li>
    <li>The checkout process </li>    
</ul>

<center>
            <img src="https://lh3.googleusercontent.com/kp6W8cD0JjYfyEKPgz5grVv1UhMIdwgd55M334zFVkUkhU67LPNwDbgnULNsvC6Key0NKp-2y8HQjWRGaI8xeJ_kpTlJWDM5Qqllx-v2NmKJd_i_jGFzj81D1d4Ng8P974eTIJLT_ZMwcvzFCtFd8n9bBSYUoU5mQHLAbIea9_SQOlTrnlzJgwawjEdVlRpexFqtukNjopshFzLiOAihcSGIansFE2qvYClkXZOQB8486lDZmSUlsjCE-XVnvb2P_REiZO2ZDZy3eoUlO0jYnkY_PLSQIcGdnXd7OmoDhUOo9FzGdEfYB187JZ0Nou_dJxUGewFs_5yKATOh0eEHBB1X5-dGYKHzP_rebDbSvNoSP-1F6ZxCuW8xwHaWyXGs5Go5KQcX7jHe-_cskGJjMI2Ejmkrrx4muXoqf8QedHSutpmE9ECrROQh3yZS5b-z6_d5NYNxtL1ivOLijooMer7in8L6h-B4mqfEeVbVOAndYZ8dql2Dfbh3TppOeDmUu_OuB6ZaR4r81vhCpDJN-t3EBdsi4fwmKHr39l8PVgL7Q4GVYFF7L0nAzdscePYKGIb_J9jiHYwlMygyo2dYcltQcjwzk-S-mIHD1XsQSnzMPdtdQ1Jo=w772-h576-no" width="40%" alt="Flow">
</center>

<strong>User flow</strong>

<p>Once we’ve analyzed the current situation, we’ve started to conceptualise our user flows. The success of a website is for me how well we modeling flows to meet the needs of our target users (personas) as well as the needs of the business.   </p>

<p> Here you have draft example of the flow we were working on for the booking of eye test. </p>

<center>
            <img src="https://lh3.googleusercontent.com/T0pR3U1Rt09qPs_o1tcfROynO4F_j7QoBnH8BgNCDjSUG3U_uUvp0HaMgq-ZvZ6-FuRL1JoPEAtnNRCWmxrf_scF8XcQEjPGsk8pm62Me1DJdS9xgqMddVUB1Q-So5gjpyMFt4jgwGkv7jfmwhK78Xt3a9_lNTFoO_tWt7zIglzb1wwTSUOYR-gOOy91KGANEOy6IzAVNlBUTkGvAnEJw1p7Muhb69Zivgy8xG_pVNU2Gdv0UcN3Oy0pA1yMjuxISMocR9NHpuq2icVg8U3e6kG0wWw43i8nUwSLNrwEpLhBumSq2uDeBG-u7Qlz-jw7C1yHcDWAQX0WKmxAE_djFQW1AXG0ZclVOu7RMD-v7KND3howI4dHx3E7hzsch0QOUelU-3k5-ITij4XdG94JsuAdvS7ss8MMw80zkzeNXQEARxWRsG0pDOsLpr00asQvQAa1K3PzhRXuXIN9_r6jxl2ccxEdEM8uxpFbad62jDQ8dvWrrgadKrfZYZwmMQx-tbBkOvwoyWjOQ-wPsDviIYst1a9fsztzeykCnxQKlg-UoqbHlynkb9Ln65w6mls8mBmU9aLDgwvZLSk2LMm1MPkqDkMf31b5BNq9PY-vC5e9a71zPIXb=w920-h684-no" width="40%" alt="Wireframes">
</center>

<p> Here you have the global user flow of a customer to buy contact lenses (offline &amp; online) after research.  </p>

<center>
            <img src="https://lh3.googleusercontent.com/x2qjYzAwpUcEtSd5hSrQVySEXT6-KHaMZpaSihPo_aX2nGcr5X3grfdHAve3afWU6UHRstxarBbbbt2DGHcyBJYanypd0KvkiqsN7jqBVdHOl96DYUvMhpyaChsbWMlpIqN5XLdjrEkTIdFOzq23dJEp-GEbGDbBBwXRRVIfl33z-pu6LxWufhUFmeG59hh6uZd7v0-JqKwwyJpQ325F1IlHlDd6LyS21xLDbamw7-6rnXB3m8Xa87exBGb4w-J2XmbT4Fqk4hIh1PPX9aFyAjBZn6mCdAOG4T_459PvixbDUvgC1J-dlGid0myJASL419QnSkZwaCQKUoQd3kCTJT5r9qa-TNpXZmNG_NzmMuydj-2TChy0xrOHdU8bf_Aq6vBUhBSYZ9rhJFxGkuBeCaLQNPgjgMqX3wb3t9XWAXZgOz112irYMW2WzR37qIvoTxL4CZked9iXsUy1DsZVKEFXtPn912-h-qY0klm1g7oTtWwy4nzGLEBaZtwzcdx0Zi3-6cZc_Hg_3UQrHlQdmwZm5qaudlhjgT133laHHt-kc3U_aQonT4YJGwGlBrxrl2GDzaVQ-lgghTi__sBsdBlAfBgUly5WkWVTJOXQX72RZ-DCPLQW=w1244-h578-no" width="40%" alt="User Flow">
</center>

<strong> Wireframing </strong>

<p>This is essential to the creation of a new feature or website: wireframing. It allows us to define the information hierarchy of our design and make it easier for ur to plan the layout according to how we want our user to process the information. </p>

<p>Please find below the wireframes of the booking system. To create them, there are many existing tools ! </p>

<center>
            <img src="https://lh3.googleusercontent.com/_6ntEQ4Y4pkSNGSy4u4d-4c5PEvgN1KjqA_fMbtmu_mBJALgt7gxSsjunjD0Ui5zBqsYtU_J3iW0at6g5pyEyNBGP92k4YYiExjguVYMD-d3vjjKgAPKWWSk3PTYMU6ZSdBR_ka1Gy2cLGOBAIf1m_GPVRnfLCGPJArjryIp0BKenDjyAKW0JwnjDczeqeYlc3_3tF9DgUuOeXAK747tITvZU7D7hy4jw-TMhYvzUtJte4Sb0GK1pOpKX1AvLPPJanouHtIFGN6-eiGEGrMSnhIbxugFJ9BIGhgHdiEvLZHK08xBmog_jDemWbkERWyLUHuaECJWDX3vkebGZxYJYtrzpaSn7Hp5lyuMcj-9CH58jJY2yMW2agjIEDEJbGydJxBznxkohalEEf0FxlgV_KV0UPmEzEyj2sh4FqOUi0F6fW7lcKG9eo3G3ABo0H-eRMnorM2w7J9sbs1SW0N1t6jqCZ86W7LBdyQu87POjg1kCXvdOe0R_tLr8xfvxSjQGeTS6IgZplvkNW764BtdEYSFjdXla_97PLlhMBYoUx6ul4-pC5UpDw2emy2qgWeNfm_egwNa2Dqi9POJKi38b2mxeFFwjK5_xGK-_EZofN6F7uUx=w1281-h730-no" width="40%" alt="Step 1">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/QNxJ7fQXJ_40JAemg-fX_rUN8T5Sap2SETD21lV5aFwgxzLKDEQsJSkR6zfFnASZrgS0t5DN6XK5oPR_9MuUncYWH4Q1eT4njbdyTFc-oq9hANEJ0bUYhFUD4iTKoHzr3mCvBzXrySG2DqMKEzQlP6vo2aD-KdxpipWeE9E8wjG3A6G7pZcKOlMwqVu_2YHEQwgA9tgq7wLDefKKTVVbFS3uzPTZrxvEwnfaFB_FLkVwwGnfFGwUlNMAJ_jawI-hPTV3MGaHigXQapMMZlWJQyx3yoFAB__xO58-DGTSD4gRmrRtM-2aaPJWqilYinmv2KnUjY9c38tt3ENCC7Ixh4SGklZpna8jdVi8NrgEPdbnQizg38bp1s0pZqcT_3QjUzQUsHtCxSQIHSJZCgpWNMPxu93oeM73ZpTW-xy5jLbCLL0gQb8_nEG0mOtRks4INILWNrsQSK6xMu2KYoJt-1Z7kNp0LsqwQRHPtMNXr8HItV9LqyjvZF70p5h5ig5RJMC7j2bHtwfjvH1Fb0K7guT4_4ifRFp9UC8XXquT0HrTSrw2NtkQdMnTeV47vIOh4ipsQOp_rp_61e7rmJZVD_qx42sod4yBqg0iGXFOGLEEZaNQ1iIn=w1281-h977-no" width="40%" alt="Step 2">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/qQxXZV2MdUwHjnDdiNOWmP6Pw30XY-jvbb0WbFUM3FGFaS4TMjEN7OPg-wvFsW7VoPaQObLbtAzlJdTfgKFXMA1ZbBZXE9ObBX_pdzQmW73JxyWlTHMQd0K84-8VmPWB0eH5ojUpZizLW2dZqPp8W9gxES8J09JgG1XvzibOds4YjxWwj5vS6yFdg6y9AqROxPLXngp1jrECssq1JdKjpcoypaijkj7erSHnieO96bOtEMsoADYcNi0KWG9hN5C45tnqWxykQGnqzbb0SOYXh7AFAvpx_uvx5yY4mkWxojePqLEQ75DekNpzsH54eOxFXSzLQBko4azUmnvtiOnZs_msiSo64GFRsUTGg7zSL5dSHBrZbaWESBfJnbxHyOk8HyhZr_B5PLZRXeQRUV-JSbm1dZOillUYopA-CiG0Ml9YXOJHdL5Fe-8H1W0Z7M2XLhqXJaumr6lbJKHGKAsrXtiehXUKPWfz4AEBteOuYhO1WQIdx5qDwD1LaKaauJH1wv7ewXk4iZlXXjTQ_5AnSqnoFRgKGrDtOYHGYnsg9LIH_w2mGfhv8wP7-mHl-uLQozHtn94dsuRqKwor6XjXznv1wlEh1xNWlj4ESO3XeXS0EOJIBoaa=w1281-h730-no" width="40%" alt="Step 3">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/MOvebPM0M1956LsGDq1q6qw-tJ8zkGZgOFcFcuclRjTmFybJQEM7txEhsBf93nWKXeMsipkyArQMbU1-gxz2hf3TqxpXIou4vSxXVFMOe3Sev2LwryZ97LevoOn3F7SDHQ6X1YhdKRrHTm6OGXJ7ao9j9lUUuLASwf9g_iBMXt_6H7Bi1dvXfrU3iRmUVbQyK2KrHAlOKH3Lil4cpmmQDiIluC2EI7WDKCnhHmjkS59FczYFQrIEOPfTRGGwzwIlUHfhOuBb6SrdBYLttMNKZXuMWonotn8oLPiAYyOfzD8v6Ty_kOekfuXg47p1adEQAhf8FPOvh1rCjRSUnqYVVOHcSusjw6fQTS-4S5fVZiYyBIJgfTrGHbXcDbx7rMu5smS8sB65MbCFtFvwPLQod44fe-PwDMwG98CeIfr6MOtOFfhYS2b8uUN79ZO6wECnfUsKZsH83VX2pWLVE4ge0wZItGQA6MNSmIO9w21I8wfZCar_vUhZSNWVP8vUI7j9p3R6Pc5jcjIgaa5bniGy65XkVwertkomHOFNRpYWYPuFGlLgaDKYX7_xES6LmJXsNHulwSfiSN0WffblXrmxii4aCZr5q_AD538ib9JaQ9cjzEi7=w1281-h730-no" width="40%" alt="Step 4">
</center>


<strong> Development  </strong>

<p>Once the wireframes were done, we’ve used an application called <a href="https://marvelapp.com/pop/">POP</a> to animate the flow. Why? It was easier for employees exterior of the team to test and give us feedbacks before we started the technical development. We’ve also asked our friends to test it and make sure we did not forget anything. </p>

<p>We’ve organised the development of our platform in weekly sprints and we’ve followed the basic rules of SCRUM Management. We were doing daily standups and weekly tests of our codes to make sure of the quality. </p>

<p>After only a few weeks, the first stable prototype was ready to be tested ! That’s why we’ve organised a focus group with different customer to test our new website.  </p>


<h2>Results</h2>

<p> Once we’ve launched, we’ve had pretty cool results: </p>
<ul>
<li>The website was 2 times faster</li>
<li>The customer needed 50% less time to find his product</li>
<li>We’ve improved the global conversion rate by 15% </li>
</ul>

<center>
            <a href="https://thenewluncher.com/sg-en/"><img src="https://lh3.googleusercontent.com/6tpoqXhldpZutcQtV_KtOnS7fwDUitEFvxh4yCKqz3iI7xI5xyi3R8xF2yg_gtCF9CCgfc0fANb3bq2vgELJ04ip-8yo55wg0yYBz1IS4ti9xjrI4sH3S93eSYgzbzUXitsArnzooxVbSMTSMk00vnhLQ-QkJ9ypp5Cfc97RR8SfQwbjuVOCuXoUz332ISQsLC_73arsqNU4z2YvemFb3WVehbWKztCIHSJZAvt7dpOekbcAB1dTYPkGog8ayXiwgbd9p_9tCwiovcec8sypXMwQ6czkCawn0AkqEZpGBqxYSJNyeGKEwuadfYYKoI2j_jBoYJ60u8ZVfM527zdHw--7y0rFZ5DcyEKeBSc0gtW3AAv8x3H5OkRsPRctI9jGDb_qFicaHXA142yRst04J50IB_aUttXHKzcvc_92kh7mKrLQumm7nj14zax-9w_iAeuURqbjpIU8RFfJpqAozVVoYX35MuNXv3wCxbolN2HsfVHXneBP7IkleNDJpArkRKuJastxS3cc6ZcdMlJV1cfqLnc19l4JzIDNh2uMMx1G2cxyJrtA379iYu2rre3lGz2maEJlbOLu26a7Ku5NQ8Up_cn3H1j1tjeORHdm-0Tvcs7l8raU=w610-h1130-no" width="30%" alt="sephora"></a>
</center>

