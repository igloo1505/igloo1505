<img src="./woah.JPG" width=300 align=right style="border-radius: 20px; margin: auto 30px auto auto; position: relative"/>

👋 Hi everybody!

My name's Andrew. Igloo comes from my grandfather's last name, Iglinski. I'm a _kinda_-former engineer with a deep passion for physics. One evening a little more than three years ago, I was reading over some of Einstein's work for probably the 15th time when something occurred to me: Einstein made an assumption that only made sense in the days before our observations that produced the concept of cosmic inflation.

Einstein was insistent on a static Universe until well into his career, including the period when he wrote the papers that gave us special relativity. If we discounted this assumption, we can produce every single experimental validation of both the specialized and generalized theories of relativity without the need for time dilation, therefore preserving synchronicity between reference frames.

<img src="./pvProbability.png" width=300 align=left style="margin: auto 30px auto auto; position: relative"/>

I quickly began to accept less work and focus more on this model of relativity than paid software work, and in the process I became homeless. Over the past 3+ years that I've been homeless, I continued to focus on this geometry, and was able to derive several physical quantities through this theory alone that align nearly perfectly with direct observation in a manner that is entirely unaccounted for by current models of relativity.

First, I was able to produce a local peculiar velocity of:

$$
v_o = c \sqrt{1 - \frac{1}{(\frac{1}{R}\int_0^{R} 2 G \frac{M}{R^{3}})^{2}}} = 526.6 ~ \text{km} ~ \text{s}^{-1}
$$

Not only was this value produced through **_local_** gravitational observations as they relate to this geometry, this value fits almost perfectly on top of probability curves found through direct observation:[^1]

Second, I was able to derive our velocity relative to the CMB as

$$
v^\prime_o = c \sqrt{1 - \frac{1}{\left( 1 + \frac{1}{2} G \frac{M}{R^3} \right)}} \approx 370 ~ \text{km} ~ \text{s}^{-1}
$$

And finally, I was able to produce a relative spatial dilation of $\frac{ds}{dx} = 1.61800103 = \Phi + 0.002\\%$.

## Fluster

Over the course of this pursuit I became increasingly frustrtated with existing note taking options. Some are easy to use, but lack advanced features while other options like notebooks offered a ton of flexibility but lacked the ability to link notes together in a way that I needed. After about a year of struggling with existing note taking applictations I gave in and built my own app, originally for my own personal use.

As my pursuit continued the features of my personal note taking app grew and grew to the point that I decided to release it as a free & open source framework. I've since rewritten the core functionality of Fluster in Rust for unbeatable performance and have migrated the original browser based application to a completely native & cross platform app, with Android and iOS apps planned for the not-to-distant future.

If you're interested in an all-in-one note taking application for modern students and academics, checkout [Fluster](https://flusterapp.com)!
