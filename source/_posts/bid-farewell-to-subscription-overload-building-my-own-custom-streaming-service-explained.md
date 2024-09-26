---
title: "Bid Farewell to Subscription Overload: Building My Own Custom Streaming Service Explained"
date: 2024-09-14T16:22:55.982Z
updated: 2024-09-21T16:05:45.439Z
tags:
  - streaming
categories:
  - tech
thumbnail: https://thmb.techidaily.com/dadc574a72620fb10d26a05d18b7bc541d4008da38e3f5b8b4a33a2f717ba587.jpg
---

## Bid Farewell to Subscription Overload: Building My Own Custom Streaming Service Explained

### Key Takeaways

* I built my own personal streaming service using a media server like Plex or Jellyfin, avoiding subscription fees and content limitations.
* There's an initial investment required for hard drives, a NAS device, and possibly more for optimal streaming experience.
* By creating your own streaming server, you retain control and avoid issues like price hikes or content removal.

 If you're like me, you're tired of seeing the phrase "price hike" in headlines about the streaming services you're paying for. I got so tired I decided to use my movie collection to build what you might call a personal streaming service. Here's what it involved.

##  How Can You Stream Movies Yourself?

 If you have copies of your movies or shows saved to a computer or [external drive](https://facebook-videos.techidaily.com/updated-in-2024-how-to-engage-fans-through-real-time-streams-mobile-edition/), you can use a media server to organize and stream that content remotely to a TV, phone, or computer. If anyone has given you a login for their [Plex](https://network-issues.techidaily.com/instantly-eradicate-playback-problems/) account, you've seen one of these servers in action. Plex is one of your options, but there are several [Plex alternatives](https://win-answers.techidaily.com/effective-remedies-for-unresponsive-qbittorrent-torrents/) out there. I went with Jellyfin for myself. If you want to avoid having to solve technical issues yourself, though, and don't mind spending a little money for premium features, Plex might be your best bet.

 We have resources if you want to [learn more about running Jellyfin](https://extra-approaches.techidaily.com/iphone-tricks-to-embrace-cameras-motion-artistry-for-2024/) yourself. Instead of retreading that ground, I'm just going to cover some key information about home streaming that I wish I'd known before going in.

##  Early Hiccups in Building a Streaming Server

 One thing I didn't initially think about was that though you can avoid paying a subscription by running something like Jellyfin, you're still going to pay for something. You need a hard drive with enough space for all the movies you want. I bought a 6TB [internal HDD](https://screen-video-capture.techidaily.com/updated-2024-approved-5-secrets-to-preventing-blank-scenes-with-obs-recording/) to start with. Now, with close to 200 movies and TV shows of varying quality, I've already used up about two-thirds of the drive, so I'm looking into [affordable hard drive upgrades](https://blog-min.techidaily.com/how-i-transferred-messages-from-xiaomi-redmi-note-12-4g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/). A [backup drive](https://discord-videos.techidaily.com/updated-mastering-live-broadcasts-your-step-by-step-guide-to-discord-streaming/) of the same or larger size is also necessary since, otherwise, you risk losing your entire library.

 You also can't forget about the optical drive to [rip your DVDs and Blu-rays](https://on-screen-recording.techidaily.com/new-in-2024-innovative-ways-to-capture-online-discussions/). My tower PC has a DVD reader, but I wanted one that could read Blu-rays too, so I bought the [ASUS BW-16D1X-U](https://www.amazon.com/Computer-International-BW-16D1X-U-Powerful-Blu-ray/dp/B071VP89X1?tag=hotoge-20&ascsubtag=UUhtgUeUpU2004575&asc%5Frefurl=https%3A%2F%2Fwww.howtogeek.com%2Fi-canceled-my-streaming-services-and-rolled-my-own%2F&asc%5Fcampaign=Evergreen). I also had to flash the drive to enable reading [4K UHD](https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oppo-a78-5g-without-puk-codes-by-drfone-android/) Blu-rays, which was a bit technical (but you can skip it if you don't care about 4K viewing). Once I got all of that squared away, though, I was happily building my library of movies I could stream from anywhere.

![An external Blu-ray drive.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/52781571646_3bd529ceb6_o.jpg) 

Jordan Gloor / How-To Geek

 Then I wanted to make my server accessible from outside my home, and that was its own job. After trying a few different methods and running into issues with port forwarding on my router, the solution I landed on was [a Cloudflare tunnel](https://www.cloudflare.com/products/tunnel/). That solved several problems like avoiding port forwarding and enabling HTTPS.

 One regret I had was where I first installed the server: my personal computer. It worked fine until someone wanted to stream something while I was using my computer for anything resource-intensive, like gaming. That led me to finally invest in a [network-attached storage (NAS)](https://fox-access.techidaily.com/new-in-2024-unleashing-potential-in-4k-with-top-gimbals-selection/) device. One of these can hold and run your server as a dedicated device instead of relying on your personal computer. There are several [streaming-capable NAS devices we recommend](https://screen-recording.techidaily.com/updated-2024-approved-navigating-virtual-boards-with-ease-a-guide-to-using-google-meet-on-diverse-devices/), but I chose the Asustor AS5202T.

![Asustor AS5202T](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/asustor-as5202t.png) 

#####  Asustor AS5202T

$269 $299 Save $30 

If you're looking for a NAS mainly for media and Plex, you can make it easy with the Asustor AS5202T. This NAS allows 4K transcoding at a great price point.

[$269 at Amazon](https://www.amazon.com/Asustor-AS5202T-Inspired-Attached-Dual-Core/dp/B07PW9DV56?tag=hotoge-20&ascsubtag=UUhtgUeUpU2004575&asc%5Frefurl=https%3A%2F%2Fwww.howtogeek.com%2Fi-canceled-my-streaming-services-and-rolled-my-own%2F&asc%5Fcampaign=Evergreen) 

 Once I got the NAS, though, I learned that a Jellyfin server is difficult to move. There's no built-in function for it at all. There are scripts you can find online that are meant to partially automate it for you, but they still require some technical knowledge to use and aren't guaranteed to work. I ultimately decided figuring it all out wasn't worth my time, so I started a new Jellyfin instance on my NAS and copied over all my movies and shows. That was a much simpler, albeit slow, process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049391/7443" target="_top" id="2049391">
  <img src="//a.impactradius-go.com/display-ad/7443-2049391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049391/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Was It All Worth It?

 So I spent a lot of time solving technical problems, and I spent a significant amount of my paycheck on equipment, but I absolutely love what I've built. I have a private library of movies and shows I like that I can stream from anywhere. No content will suddenly disappear due to licensing deals between the Hollywood powers that be. Since I'm using Jellyfin, I can't be forced to accept price hikes or watch ad breaks.

 Not only that, but I also have a newfound drive to find interesting content to add to my server. You might be surprised by how many movies and shows just aren't available to stream, even via rental. That gold can only be found in thrift stores and on collector's trading sites. I'll take pilfering a $5 DVD bin over [endlessly scrolling Netflix](https://video-screen-grab.techidaily.com/straightforward-steps-upside-down-video-rotation-using-vlc-for-2024/) any day.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



