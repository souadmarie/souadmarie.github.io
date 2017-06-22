---
layout: post
title:  "From a technical issue to a new website"
date: 2016-09-01 00:00:00 +0800
categories: SeeChic
---

<center>
            <img src="https://lh3.googleusercontent.com/C2oQBLPgw7vPWcDWNGM9tvopLIpxmQ-OENhYfUvedaqWEtgj5yL0MblnsAcC45RvFLGqpxsSnU_LAwvM7X25yhqs9xNUXiXs9sSQBqFPspZUiq5dBVyb8y_SbOzReY39A2tuCPcxeKjixWv_3rx_suGm_Qw5nmV0MuanWSi5-o-JHzs387ZNMYjhhppnheu2EBQ9Lb2BNyVyhB-3UjglK8lWYk6TaJw6jdH2b88ZjXYdvn3ZSkJrgA4xgljLK0YZenpduAIZ9Yx6Z4Sffw3LUfdKqOUEx9_Jf_ZS_VBc_wfd7qVpBcZsnl7UL5uScfx6xIM5aoYNTcmdPPwyWyN2gGGBbVNnh5K4w_YDxsYwcvx_R2YtZYKw6__OFKvXibJMUhkm0XymEj2Bqvh6SmMbEbwoDvVZxsqoB0o3r4_HWUgm4Rd5L5aYj0FdhbQELxt29OrChHU_x2MtuZlm04HerQhVuftRIE4hn2gryN8Xz7BdKRveI9DnU3ep-nlE_nuSvoZwtQNOI610nWIiAv-HqFdjACZIZQE4dW9IB-DG40bxPjR4qHKG-vebRUNJvQ_gHDV5HpF4Id311sHAofdQaO5Q3cDqYG-WzH2lEs_H6kkKig2UPwn7Hr5sr2_wDIQ2HQjKv3T_JC3IZlSxg9dbzoHaVDojSw9Sz1MoUDShOw=w400-h150-no" width="40%" alt="SeeChic">
</center>

<i>SeeChic was a contact-lenses and sunglasses e-commerce platform in Singapore, created in April 2015. </i>

<h2>Problem</h2>

<p> Contact-lenses are very complex products to sell online, more complicated in term of technology and process than clothes or cosmetic. Given a contact-lense product “1 day acuvue moist for astigmatism” - on its own, this product has thousands of variants that depends on the customer prescription.  </p>

<p> Our problem was to provide real-time stock update on our website for more than 50,000 variants while using a CMS called Magento. In fact, the technology chosen to start was not the correct solution. Magento is a good solution for simple e-commerce business but it was not appropriate for our needs. </p>

<h2>How to fix it?</h2>

<strong>Analyse</strong>

<p>Once we took the decision that we needed a new technology for our e-commerce platform, we started to analyze our current customer behavior. For this, we’ve used mainly Google Analytics Conversion Funnel feature. Here are the differents scenarios that we’ve analyzed:</p>
<ul>
    <li>The completion of the prescription to the cart </li>
    <li>The sign-up in order to take an appointment with our optometrist</li>
    <li>From the landing on our website to the product page </li>
    <li>The checkout process </li>    
</ul>

<center>
            <img src="https://lh3.googleusercontent.com/E4lT4WYklh16P1Yjz1mT99WhT72DT79kY2WVD2DuJo1gzvRmoxt6LcTNfRzi3j6RBibOqqpbrh9bNLV6dehZ3S8TMrxBpze5MI7hw3yrbei-LISNOFmvm5TPoNDT7KqNiDUPIcK720kzmCzkWJ-RIrzYEfOCcm6829x3qGNo4wGWelKotzxtHEtw3p8akeXfBjY9Lk_FxkPfOhUWsgHHnpLmM0jQqOwxulYmtvURAUFYfn02QlKJF9OmPOD877trkZtkTvC5vBIB8XJ6hAAcdOO6cGiVZ5Ws6CQkD2iL2wv3rRKgcvLXhDQmQwr7C_nMpWQCPjqhhN6Z7nxQxyaWfExQq-GbOtOawtY0cBgRszaoh2JMUFtPyiZH78p_hE0I5qnwC1whyXyl7VbjbT17rgCXtEQo5zbk4B_C5kmr7aUlOwUKEVF-fLoLVCHSEzjRTGv7ALE-H61o3X87PwXWxt2ucLN0FSi6DI4iuF1pEBfuGcf48uIg0QdcrERkfZxyfdQYTtR6N-kPrO0pZOrUdq7f06nWm0i3vaRDUoMdfJ8hfTd4vVVqrIYS4TW9Tll_vMCn0U8yhaOcMssWDG6ftqSXjKMA00-nmGTMqpiRVsEcWg2NktIGR3WD4ch_cH9OD0zGiTzdYmGQ01vSMi7jLXq5EgFIJdTEeYO_nKbalA=w772-h576-no" width="40%" alt="Flow">
</center>

<strong>User flow</strong>

<p>Once we’ve analyzed the current situation, we’ve started to conceptualise our user flows. The success of a website is for me how well we modeling flows to meet the needs of our target users (personas) as well as the needs of the business.   </p>

<p> Here you have draft example of the flow we were working on for the booking of eye test. </p>

<center>
            <img src="https://lh3.googleusercontent.com/wJKSdoH_KXGs_xVWUzYJit_ueRsjlzPNzKS562CkhpSAdLFaodxF3jyJj8OEzn3c6G3Kqr0_wbeOQrrX505o_XdazrLY9o-GzMnjzQXzsHWQ0JLt5XVLLZhXokcEVowgtXPza4Gr4iH_B4jAwfXy6Rmll3X8hpQIYKg9xOZJuZhuPJvrE7XQNQtnt2qaBL7DAs4rw2GUIaJjiMXFBt5mjITUytCuiAHzYh_teZixnAMM1LLAoQpX9WOUSoMLWqRE6aEKELBP-y--P6dzrFbJ4H5YAgcFpfjauU0oM8CaWewjpfosR28zarYAHan3IJ8vTrY2ro227g1k28IFXCO2nMlybwqU6ETD9TBeJp7kf5ZDuB54l5ni7rrZMBOVwel3ygFRzr46uOIafZ8QWA-RvwyEJR0oi-dkHM1tmg2_aokSVrs2gjBlcTJn5H5b7QwydQrtNCSkE0OJ7Xvk-QRN-l4oHwe8Ps4VuZInXIfSW87m7TdkoC1vtqzCbbeEX0LMIyX0CPkmudhcm3JWWt9bBm8anaWlsb59FHtydR3-eLXmr5pEhvcauGUF2mp5VhAzJD6bpjvK2TrEUbLb440NFCCN0tVeHFJHFYr8bsWvEiRkaL2IdlvVz7ipUzCLz7tCWYACIvPR68zTLCsLuod1ZQx_KMd_S68uL6qTn7hcqw=w920-h684-no" width="40%" alt="Wireframes">
</center>

<p> Here you have the global user flow of a customer to buy contact lenses (offline &amp; online) after research.  </p>

<center>
            <img src="https://lh3.googleusercontent.com/gAJEL_ivmzfoBRlk_XYPsv33itBMYLFZRmE0MxmsU34PlcJNCSs26tK3aMZ2w9nzfITXBAFzDBkJxoCGGsuJqFeiSlmNnXDFH8sy8cqh3BCf-rit1gJqGzHrhkXrTskvpS0rAk29f3He7HB6NRJbrB7MbUvqiv9FFQx6EmjcWO4o5qv4BjNOr234nPjjHM9NO8axkTpuVEYnFwk7ejfl9PauQWPwKTwGp-q9NSrImeS5CRCSH1C0KP7Q3U0mjpGJusnktxr_QNdK7iF11-TuB9kq4BbTuG8A2-pkhY81ZNpp8fz51ZCCw1Tb63IXUJBuD6clIN3m3vcxALCTPUAIBLdchgo3jDijFqYOM7A6DJunxG-srGTQMovgdOweSqXrWka4UtDrnhW3sodEpd-xvc12crq3K1MrTNx4oZOf6QA953tmpDhPje4aHeKyEaz93G_MFcQVP9OSJkSWJrJrfJn-RIeZAJz4KJQcQgOjeZVuezaK9Hk0JbdtLSMu39pBFxyhTzFofJZiUhgiInVY8zBqfYOeQNojGjV78UDHoxhPUqYsJj_k_v2g5Y55k3QbxXPoPv8gWsd5LiE5-0tD8SWgjhj36Mb6AxY4KpHIHNqr0VKXgFTaNLqE1RLapZhOo85wg3MeIXrmmCHYG5zBlZB3Tgvke6OP1hgNWky05A=w1244-h578-no" width="40%" alt="User Flow">
</center>

<strong> Wireframing </strong>

<p>This is essential to the creation of a new feature or website: wireframing. It allows us to define the information hierarchy of our design and make it easier for ur to plan the layout according to how we want our user to process the information. </p>

<p>Please find below the wireframes of the booking system. To create them, there are many existing tools ! </p>

<center>
            <img src="https://lh3.googleusercontent.com/ASm1d-LLGa322Nb5r6bQp-nmDZXPzJMuMpBKNVz1WRCyElZLBYSjp3GTlfDdUwGcpz3P0RahSlBZLaJsc6_PEH6RKRs4ZRdHDw1dh0tsDm7V6z2H9W0MKSVzOFkq8y_ZiexjgUH4HfjhehS_UsNl9KgQe4x8Wq2NutREDj1eN0J2_hoeP019KJRQQXy53yb81sz_X78UAIR5KK8J34ODlSkBhmGHarSWcKJGbBSNidTT3oV5KG85SyUhQoPChxKKUhyo1f1XL_K5Yaq_xzbNI2tnWoMGZ3FQAlYvGUOxSl4UX0gIbsBgZLm-EnhoW8LmGcs0VEA0NdfdwvygyZqGZXLFUfw6hGBHEMv14hjRQ5hsFlxwFf7mDK87dd75Db92VgbUs-m-JE9MHnt6_rtAuWvfjiwltB0bjVu8s_Z6CwPtgheNPOSd7x3dcNFiXtcPQJjSYpl4DzM42GH5uGDGbNY2RIE9gt0hAWySSQHMOrnxwqkAoSf4NA0pNfycTr8grnJ8PTa6pwj8ew2NwGKKL8QjqDEUbPW0a8qQWR9XfJ23iFh-0yys0oXCBgx34NoGPjgM0b2Qsg_zzRHOOCkKSmSufZaVN7vc_CgHFpFJ3vwfGikBeRgLQlYlHktCz5MH-Oli28MjUregZFXtMdZEwhK4i50KMDAe3duHnTNwbA=w1281-h730-no" width="40%" alt="Step 1">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/EoJcG5G3xNa1VhRWhlNyXNRyhE8fMuKdFk50B5vqlSEZ4aQBEOvW_S4ofC1_fc38WY7zLQx-KBxwusx-bAEkN1AlPCAhqOZP4FIgPbPfS7Xit97sgAfp0B4UxHdpjBf-rJ0V5HgFz67Cz8A-60-CIdiriaEFf51FvrBxmJWzGY1paIg3mkZcOyIdVmsi8DXsffjURKWz2v-XTxcXD0hJ7FbItVDgeE-FQMXxC2-H41BiHGTRLBGSxJqu1tfb8wrTdlCXxSnig7MYNYVz4LUt6wB_fRBCTTiSYQYJT6DeDHJ9AVxadsFj7148eY9liMgwE6uvj2sq6rnejuhBFlOsfOyumlks15WietrL3QTgAs5NuKWN34qzMhTet2BtpoiBAl0Mt4ziU6QM97E-tHNK6Nvg2Z3no4-pQ_xcBoEa88KfJZHm9p1gNXvWM63DU9xPwSKKj_1UFK3dSGGfodc2ZcZ13mxcUsw53C25bYhCaTk5outAu73101eFpqSTJYOD8mUf95nCr6DmMvS5YoMZ_9eSIr6i28BAlaSXSVMMo5QN2ofIIMXsy4E91Vq4Uzcy85gmB_CJ99N4jYrYzMf1VuXerWPZxOgTf2j-1LF2j37mxAsc=w1281-h977-no" width="40%" alt="Step 2">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/8QqChEB2CJkN6kWldo9PQRWTCf5dncvtAfWiTwS-hE_b07eds5-YYttbrVa4MS-LeEHxPXgsKCZ1fZyEKngnZ7L6p8xQVKwLt0rRc6JgOXNokNrEqQ378eyVIhc-86h_b4d51ULmPnt3YeOSF__5tgI2z2z2yWAINbNoruNyEa7qhmMgPwIOi6CVQS_5l99NSmbaFcZGngCmVJapbCs79Jftu-CKKp_gb4yUajOfsmSyRHHeUJFgGHUZ9Y4mA6TjkXbDp_pB4FlZTNat_11Z-A067w5DPQFVMiieWYyGDO8R8bqvdHFIFB2R3ZQh7-Yn6yP3RJ9RVPPEZFS97dwzBjRr-HGLSPD46Qllq8yVWkpPUm7MxZnCCByBHuPSX8kVOiy2X7QDKe2DhO9O8m5Mh6qx5XpwFpxLD_HTYM0BfXgGwb2AXrimb7bMsmBYXIrtjQldvNvxDqmeHdWSoE6nqHtn4TCO758BW6EJiL3qAeg9a5pZjwhhi5M0WG90BTQaP6l-kQ5vupa_aqGVG42otVSH-lqBPGkCnox3kB-qnzcGjxpsRi3xc0SHEq71bTcpURDeZUQZgiFD_PWhCwlPcBJgmBLIwPwuOpqDvcCE3eQ97GnTqA5NK1cB-npkQt62B6ItKxq7_ioD_zb26Ab_94FKSvffn_bfXB4bsGM0CQ=w1281-h730-no" width="40%" alt="Step 3">
</center>
<center>
            <img src="https://lh3.googleusercontent.com/SnCRdPCOEmhG7qmTOeIBMIPlmNaE0hzaKb4V1nZeK4rLMZdNBgKvFwEMfBLHcyRgbJkY3NaFJlFUQqh9PVQxTzqzVtkLnOqnVVBqzRSYXvcIXuIwADh6j6nuZ473bWk5LFxkKltSCIV5EkrZiRlEVj54guLWHGVwcyhbZMhGlfZOlIsmUt7ffEoo2xNWRGPICEWxpz6jN7YVmX1SH7i-xO98YLqtb2R8EmpFSBUh4Pl7AxFmVlqhaWdIamFKdLNynv-zzMlbFSvNBsjD6pIsV4IQOgW4QGy3_PSpM-HPGpXAPcqXWxLxSTRNp7vzcfNhPaDrBGHhqYWKXF0AyKJoNtrq5OPL1wNVq7VMZe3D-mykaAH3fj8jB1eljAl0zPYGtodoOcMLfDZ4Qv6Zy9eGCxxXh9OPv8iiXh_3PYijVTGTlEoSWJMCgu0ulGQIB9bNskShItKXZZ2aXb-00TQK8JGLTYRak2vJNXsDy5DoAtgk7BljsuUl8p9-SMl-efRlP20f-tVr5pey5lH4qO85wv1jZ6FqYlhyiH-l8mKa8fIMixy4WKu6EALUZajBgjoKgoNcg2CjXD-QrErez5TIx7XlhbyOrCdqG4al_8JOaN84ZIXx=w1281-h730-no" width="40%" alt="Step 4">
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
            <img src="https://lh3.googleusercontent.com/S10cbl3yo9mo5DwHOFLY0AK-hSXfSFhAZ4qAIU0FuUIqPiwFuM3SSUTbDLGbgwbaPUMfiKox230uX45o_wtgPqWhAF3kExNThi5ObB1o4qhIL2Vzek1vRqsYWejVJFvubm0fSX70AVdGG792pUuWd4nPm4NxHjdwr9xmAY7nNcSvkNsXky3owpbXtK5-3SibNcyvCK5bKmmt13bDJKn7Xprgy5WrJf0qLpyeALrJB9UUDwKaTvR-sMIZZmAEaSASREgoByVNpNF5qE7CH0TzCJopFabXQU8n82g8F9BmXnicRR07n3_1caItXc7OFGu-dCDbKXjas5VxwbypCEZwZKWhlhEjpy42jlCy9jqYBu1eZ0wV8xi2ki7oSfpzDS7ai8J4MYyfGZ6KFghb2KMDX3H22V_1psIeb9biE7oTHQr5ChSAV8axnmW8wX0vbA5CLLMkW02IvIl6qejH8OTF-CMZsvxJNiWG4H_Lf1-rxPaZmXaafLC-h0wez9xE3eA8mgQ9aSM1GvgCrujkT2xjjyQmgZzpbNiHGcGJu_zXcXFnp__mCDwOS0rSZB5aJDYqIZsBeM2fqf6WrZ2mznZxFlVvzzM0Tezo7mKyHICsAChTDWQhs9IO=w610-h1130-no" width="30%" alt="sephora">
</center>

