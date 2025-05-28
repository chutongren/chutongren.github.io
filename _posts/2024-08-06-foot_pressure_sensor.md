---
layout: post
title: "Foot Pressure Sensor And It's Usage In Barefoot Shoes: Fullsoul Runningpad"
subtitle: "to measure the foot pressure distribution in real time"
thumbnail-img: /assets/img/fullsoulWalking.jpg
tags: [python, data analysis, data visualization]
---

I met Kai in a lab where we both preparing a project for another course. While chatting during a break, he told me he had a skiing accident four years ago, which left he still feel pain when lightly jogging. In his search for recovery, he stumbled upon some curious insights: Hippocrates once said, “Walking is man’s best medicine.” Daniel Liebermann believes humans are “born and evolved to run.” And Abebe Bikila won an Olympic marathon barefoot. Really? Could barefoot walking and running truly be this powerful? I was curious too. So, with this curiosity, we began our project for the Clinical Applications of Computational Medicine course (24SS).

We want to find out if we can qualify and quantify the benefits of barefoot shoes.

To explore this, we integrated [a Velostat sensor](https://www.moxiantech.com/) into [the barefoot shoe designed by our Prof. Dr. Martin Daumer](https://fullsoul.de/). Then we walked on grass and on stone comparing the data from the barefoot shoe to that from a regular shoe. [The code](https://github.com/weichkai/footPressureSensor) is uploaded on GitHub. 

The results speak for themselves: barefoot shoes like Fullsoul provide more detailed, direct feedback from the ground. The pressure is more localized, the peak values are higher, and users report feeling more connected to the surface they walk on. In other words, barefoot shoes don’t just feel different - they can be measured to be different.

For example, the following four videos are in four situations: sensor in the fullsole, sensor in the normal shoes, walking on the grass, walking on the stone. Our experiments show that barefoot shoes like fullsoul allow for significantly more detailed and direct pressure feedback from the ground, compared to conventional shoes. This effect is not only subjectively noticeable but can also be clearly quantified by higher maximum pressure values, more localized pressure distribution, and an increase in total pressure on uneven surfaces. These findings support the idea that barefoot shoes enhance sensory feedback and ground awareness, which are considered key benefits in the context of healthy walking and posture control.

<style>
.video-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px; /* 控制视频之间的水平和垂直间距 */
  justify-content: center;
  margin-bottom: 40px;
}

.video-item {
  flex: 1 1 calc(50% - 10px);
  max-width: calc(50% - 10px);
  display: flex;
  flex-direction: column;
  align-items: center;
}

video {
  width: 100%;
  height: auto;
/*   border-radius: 10px; */
  margin-bottom: 4px; /* 视频和文字之间的间距 */
}

.video-item p {
  margin: 0; /* 去掉默认段落间距 */
  font-size: 14px;
  line-height: 1.4;
  text-align: center;
}
</style>

<div class="video-grid">
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/fullsoul_wiese1-lessthan25MB.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">wearing fullsoul on the grass</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/nrshoes_wiese2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">wearing normal shoes on the grass</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/fullsoul_stone1.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">wearing fullsoul on the stone pebbles</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/nrshoes_stone2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">wearing normal shoes on the stone pebbles</p>
  </div>
</div>

<iframe src="/assets/pdf/foot_pressure_sensor_presentation_06082024_v15.pdf" width="100%" height="800px" style="border-radius: 15px;"></iframe>

_if you are interested and want to learn about more:_

So it all began when Kai went on a skiing trip 4 years ago, when Kai found himself hurtling down the mountain similarly to this poor dog. He ended up in the hospital with three torn knee ligaments. Even though he had two Operations he still feels pain when lightly jogging.

When he was researching ways to improve his situation hoping to get to a point where he could run pain free, he encountered a quote from the famous greek physician and philosopher Hippocrates, *"walking is a man's best medicine"*. Researching more about this topic lead him down a rabbit hole of walking, running and especially barefoot running. It was at this time, that he also stumbled upon Daniel Libermann.​
​
Daniel Liebermann is an Evolutionary Biologist and paleoanthropologist at Harvard University. He has studied the evolutionary aspect of running and believes that *we as humans are "born and evolved to run"*. He focuses his research on the health benefits of barefoot running compared to running with modern shoes. He believes that running barefoot more often could lead to pain free running and less injuries.​

In the video Daniel Libermann shows a comparisson between heel-striking in normal shoes and forefoot-striking when barefoot. The argument he makes is that when forefoot or midfoot-striking which happens when running barefoot or with barefoot shoes, the biomechanics of the foot are allowed to work in a more natural way and can better reduce impact forces. Over time this reduces strain to the joints and lowers the risk of pain and repetitive stress-related injuries.

In an article for the Harvard Gazette called „leave those calluses alone“ Daniel lieberman says that humans from an evolutionary standpoint have always had calluses and that they actually have a purpose. Not only do they protect the sole of the foot he also discovered, that "no matter how thick, tough, and crusty the skin on the bottom of walkers’ feet became, they could still feel the ground as well as someone with virtually no calluses."

The fullsoul is designed by Prof. Dr. Martin Daumer. It is an ultra minimalistic barefoot shoe that consisting of a single thin leather sole. There are straps that go through the toes similarly to a flip flop, the straps also loop around the sides towards the heel to keep it tightly in place. Apart from Prof. Daumers fullsouls there are several instances where minimalistic barefoot shoes are being used today. Author Christopher McDougall, together with Daniel Libermann investigated an indigenous mexican mountain tribe, the Tarahumara in his best selling book Born To Run. The Tarahumara have a tradition of running up to 300 km through mountains and valleys, over two days, with only Huaraches, their traditional barefoot running shoes protecting their feet. 

Kai has japanese roots and was suprised to hear from Prof. Daumer that there is a group of barefoot runners in japan that some consider to be the best ultra runners in the world, especially since Kai had never hear about them. To become a marathon monk of mt. Hiei one must complete a grueling 7 year trial called the „kaihougyou“. During the last and hardest year of the ritual they run 80 km a day around the rocky paths of mountain Hiei for 100 consecutive days. The only protection they have for their feet are traditional japanese barefoot shoes made from straw called „waraji“.

Another example showing that barefoot running can be extremely effective is Abebe Bikila, a barefoot runner, who took the world by storm when he finished first in the 1960s Olympics Marathon without shoes. 

But how does all of this fit together?

First there is Kai‘s personal motivation to run pain free. Then we saw that there are barefoot runners that execell at what they do, and that barefoot running could prevent pain. Lastly we have seen that minimalistic barefoot shoes like the fullsoul have been used to protect the feet whilst still keeping the barefoot feeling. *All of this together brings us to our main goal! We want to find out if we can qualify and quantify the benefits of barefoot shoes.* Can they help develop healthier running styles? Are modern running shoes inferior compared to minimal shoes or even barefoot running?

How are we going to achieve this? Well we have our sensor. After building the velostat matrix we connected it to an esp32 microcontroller and an ADC to reproduce how the shoesole sensor measured the resistance at each point. We programmed the esp to sequentially set each row to high. For each row we would measure the resistance for all columns. This leads to 9 values per iteration. For demonstration purposes we added an led matrix where each led represents one point on our velostat matrix. 

After figuring out how the sensor works, we wanted to analyze its characteristics.We first looked at the sensor Hysteresis. The Hysteresis is the dependence of the state of a system on its history. To measure it we loaded and unloaded only one of the 156 electrodes with weight and measured along the way. We found, that the sensor did not output the same values at the same weight. Over 20 trials we discovered that the peak hysteresis was around 10%.

This affects our sensors accuracy and shows us that quantitative results should be taken with a grain of salt, however qualitative results can be trusted. While we were measuring the hysteresis we noticed two things: the amplitude of the hysteresis could vary from day to day. We believe that this has to do with the sensors temperature dependency. Unfortunately we do not have a controlled environment where we could characterize the temperature effects. 

The other thing we discovered is sensor drift. What we understand under sensor drift is that with an unchanging weight the values the sensor measures change over time. In this graph we see a timeframe of 30 minutes. In the first 15 minutes the values the sensor outputs increase over time. After 15 minutes it seems to become stable.
Since this is an attribute for static load which usually does not happen during running, we believe that the influence of sensor drift is minimal for our application.

We noticed that the sensor is not completely linear. For low pressures the sensitivity is low, then there is a non linear transition phase for medium pressure and at higher pressure applied to the sensor the curve becomes approximately linear. Since we apply our entire body weight as pressure, we can assume that for our application the sensor output will be mostly linear. 

The last attribute we investigated for sensor characterization is channel crosstalk. How much does a punctual pressure impact neighboring electrodes. We found that the crosstalk was minimal, usually under 3 % for direct neighbors. We believe that this effect is negligeable for our purposes.Interestingly we only found either horizotal crosstalk along the rows or vertical crosstalk along the columns, but never diagonal.

With the help of Prof. Dr. Martin Daumer, were able to integrate our sensor into the fullsoul. It is a sandwich construction where fullsoul, sensor and and a second layer of leather are glued together with a special glue. Once this was accomplished, we were able to move on to testing the "sensor fullsoul".

First we chose a relative flat surface like this grass field. We took measurements with the sensor fullsoul as well as with the sensor inside of a regular shoe. We also recorded the whole process of walking. Next we synchronized the data with the video. 

The graph shown is the average pressure over the entire foot at each timepoint. The image of the sensor to the right of video show the pressure recorded at each point of the sensor at each timepoint. What we found was pretty much exactly what we expected. The thick sole of the regular shoe distributes the pressure very evenly across the entire shoe. In the regular shoe Kai was not able to feel the structure of the ground at all.With the sensor fullsoul however things were a bit different. Even though the grass field was relatively flat, we can see that individual areas show higher pressure values than others. This was confirmed by Kai, who said that he could feel small bumps in the ground that he could not feel before.

This effect was even stronger when we moved over to a more rough surface: stone pebbles. On the stone pebbles, Kai immediately noticed the difference. When wearing the sensor fullsoul he said could feel each stone pressing against his sole. In normal shoes he felt that he was standing on a somewhat unstable surface, but he was unable to fell individual stones.This impression is perfectly represented in the data. Similarly to the experiment on grass the fullsoul shows significantly more pressurized areas. The maximum pressures recorded are larger than twice the highest values recorded with the normal shoe. Even though the total pressure over sensor fullsoul and normal shoe were quite even on grass, on stone pebbles the total pressure is around 10 % higher on the sensor fullsoul. 

So let’s recapitulate what we did so far? We were able to aquire raw data from the sensor. We managed to integrate the sensor into the fullsoul. We recorded data with the fullsoul on different terrain and compared it to normal shoes in our own GUI. And we got in touch with the manufacturer. All in all we layed the groundwork and got some promising first results that will have to be tested further! We were able to get some feedback to our final progress from the Director of the Schön Klinik in Munic , Prof. Dr. Markus Walther and also from Prof. Dr. Daumer. Although there are some competitors in the field of measuring foot pressure, due to the way their sensors are constructed none of them will be able to integrate them into barefoot shoes. So far measuring the benefits of barefoot shoes was a difficult task, that usually required a pressure plate running setup in a laboratory. However these enviroments do not accurately represent real scenarios.That is why we believe that we might be developing a unique new technique to measure the benefits of barefoot shoes!

Even though this course is over, this is just the beginning of our project. There are a couple things we want to accomplish in the near future: First, since it is obviously not optimal to run with a cable dangling to the side of your leg, we want to make the entire device bluetooth capable. The Manufacturer says they also are working on a bluetooth device, which we could potentially use in the future, or we expand the proof of concept circuit that Kai talked about earlier to work with our sensor, since the esp32 microcontroller is fast enough and posseses bluetooth capabilities. Then we want to find a better way to integrate the sensor into the fullsoul. Due to time constraints we were only able to glue the sensor in place. This glue did not hold too well and came loose after a couple test walks. We believe that sewing the sensor into the fullsoul will result in a stronger hold. In the future, after we have done enough testing we want to be able to customize the shape of the sensor to fit each shoe size and foot shape individually.

Dr. Walther has prepared some tools for us with which we want to prove the hypothesis, that a thin leather sole like the fullsoul has, does not impact the foots ability to feel. Dr. Walther also recommended us to look at serious runners as a potential target group, since getting medical certification takes a lot of time and money, whilst individual serious sportspeople can be a great way to quickly acquire lots of feedback.

Lastly, we will do lots and lots of barefoot running :)
 
We want to give our special thanks to Prof. Dr. Daumer, for donating a pair of fullsouls for this project as well as providing his experties in the field of barefoot running. We also want to thank Prof. Dr. Walther for taking time out of his busy schedule to discuss possible applications of our sensor fullsoul in the field of medicine. Without Lingfeng this project would have never been possible, since he was the one who supplied us with his sensors. And last but not least we want to thank Yuan and Marco helped us out with some of the sensor characterization measurement setup and data and video aquisition.

If you found our project interesting or are interested in barefoot running, please feel free to find us on github where we have uploaded all our work and also descriptions on how to replicate our results.
