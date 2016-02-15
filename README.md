# Gate?
Gate is a mindset to build simple, modular and intercommunicable applications. We create tools that have one purpose and one purpose alone, with non-obtrusive interfaces that making people agile.

# Products
## Halflife
There's a URL for each Facebook Page. There's no page to see everyone, or create a new one.
This project aims to point out the best moment to amplify a Facebook post based on the HLR, a metric we created to summarize the virality of the post.

### Links
 * http://halflife.gate.cx/#!/coca-cola/columns
 * http://halflife.gate.cx/#!/guarana-kuat-oh-yeah/columns
 * http://halflife.gate.cx/#!/kitkat/columns
 * http://halflife.gate.cx/#!/nescau/columns
 * http://halflife.gate.cx/#!/nestleninho/columns

### Data
We collect the following data from Facebook:

For each post:

 * Text
 * Link
 * Picture
 * Post creation time
 * Page
 * Was paid?

Everty 10 minutes:

 * Reach
 * Organic
 * Viral
 * Paid
 * Comments
 * Likes
 * Shares
 * Engaged

## Kolab Dashboard
The one Dasboard to rule them all.

### Links
 * https://dashboard.kolab.cc

### Data
We collect the following data:

 >     Admotion_api
 >         Somatório de todas as Impressões do mês
 >         Somatório de todas os Video views do mês
 >         TRP de impressions (Calculado usando Profile Index)
 >     Adwords_client
 >         TRP de impressions (Calculado usando Profile Index)
 >         Total de Clicks
 >     Comscore_api
 >         Profile Index
 >         OWNED
 >            COCACOLA.COM.BR
 >         PAID
 >             TWITTER.COM
 >             FACEBOOK.COM
 >             VEVO.COM
 >             YOUTUBE.COM
 >             Yahoo
 >             Globo.com Homepage
 >             MSN
 >             BAIXAKI.COM.BR
 >             TECMUNDO.COM.BR
 >             MEGACURIOSO.COM.BR
 >             TodaTeen
 >             LETRAS.COM.BR
 >     Expion_api
 >         Deprecated.
 >         Data
 >             Facebook (Now we fetch directly)
 >             Youtube (Will use sprinklr)
 >     Facebook Ads
 >         Data
 >             TRP de impressions
 >             Reach
 >     Facebook Graph API
 >     Data
 >         Organic TRP based on organic impressions,
 >         TRP based on earned impressions
 >         Fans count
 >         Total reach
 >         Total engagement
 >     Google Analytics
 >         Data
 >             TRP of visits using ProfileIndex
 >             Visits
 >             Time on site
 >     Google Docs
 >         Data from Coca-Cola that we can't get from the API
 >             B3
 >             BrainJuicer
 >             Nielsen
 >             Packm
 >             OOH
 >             BGS
 >             BGS
 >     Ibope
 >         We need to upload a CSV
 >         Data
 >             TRP of Merchandising
 >             TRP of TV ads
 >     Imusica
 >         Data
 >             TRP of connections
 >             Engaged users
 >             Time spent
 >     Netbase
 >         Data
 >             Twitter
 >                 tagcloud
 >                 mentions de @cocacola
 >                 NetSentiment
 >                 Buzz Earned
 >                     Total Mentions - total posts #coca-cola (no filter)
 >                     Total Impressions - total impressions #coca-cola (no filter)
 >                 Impressions
 >                 TotalBuzzPost
 >                 PositiveSentiment
 >                 NegativeSentiment
 >                 TRP de impressions - Positivo
 >                 TRP de impressions - Negativo
 >             Instagram
 >                 Instagram Earned
 >                     Mentions
 >                     TRP - total mentions (domain: instagram.com) / TARGET_UNIVERSE * 100
 >     Paid_video_metrics
 >         Dados
 >             Youtube video views
 >             Facebook video views
 >             Admotion video views
 >             TRP da soma dos views usando ProfileIndex
 >     Twclient
 >         Dados
 >             Twitter
 >                 Followers
 >                 Retweet
 >                 TRP de Followers (Precisamos verificar possível BUG com a Vivian)
 >     Webtrends_api
 >         Dados
 >             Youtube
 >                 Views
 >                 TRP de Views

## Media Database:
Aggregate the median plans from every agency.

### Links
 * http://mediadatabase.kolab.223.io

### Data
We don't save anything useful yet.

## Bid by weather
Control Google ads based on the weather

### Data
 * http://www.wunderground.com

## NLAB Dashboard
Like the Kolab Dashboard, but for Nlab(Nestlé)

### Links
The login can be made in any Dashboard, or via Hub(McCann SP product).

 * http://ninho.dashboard.nlab.cx/
 * http://nescau.dashboard.nlab.cx/
 * http://kitkat.dashboard.nlab.cx/

### Data
Google Spreadsheet

## Paranoid:
One timeline for the major social media: Facebook, Twitter, Instagram, Youtube

### Links
 * http://paranoid.gate.cx

## Gate.cx:
  The login hub.

## Radar MTC:
Marketing the category made easy.

A email that alert you if anything unusual regarding the brand category is starting.

### Data
We use data from Google Inisights

# Values
## Why does it matter?
[The Conway's law](https://en.wikipedia.org/wiki/Conway's_law) says that we are constrained to produce designs which are copies of our communication structures. So, the work done to improve these structures is worthy.

We are building upon three main foundations, Small Acts Manifesto, The Zen of Python and Wabi Sabi philosophy.

## Small Acts Manifesto.
Written by some amazing Open Source Communities from Rio de Janeiro, [this manifesto](http://smallactsmanifesto.org/) ruled a lot of very cool initiatives and now is one of our bases:

 1. *Trust* - which must be respected and never put at risk;
 2. *Dialog* - is the way to establish a truly trustful relationship;
 3. *Personal* Contact - the richest experience, not matched by any media or technology;
 4. *Transparency* - the mean to maintain a sustainable community;
 5. *Diversity* - people have many interests, but if you need a label, label yourself as a human;
 6. *Self-organization* - leaders come and go, but there should be no owners;
 7. *Example* - that's how you teach, live and learn;
 8. *Consistency* - things take time, intensity is not always the answer;
 9. *Give, give, give!* - you'll be impressed by how fast things will come back;
 10. *Do it!* - as simple as you can, just what is essential to pass it forward.

## The Zen of Python

[This poem written](https://www.python.org/dev/peps/pep-0020/) by Tim Peters has captured the soul of Python programming language. We believe that the tools we use plays a important role shaping not only the products we build but also ourselves.

 > Beautiful is better than ugly.
 > Explicit is better than implicit.
 > Simple is better than complex.
 > Complex is better than complicated.
 > Flat is better than nested.
 > Sparse is better than dense.
 > Readability counts.
 > Special cases aren't special enough to break the rules.
 > Although practicality beats purity.
 > Errors should never pass silently.
 > Unless explicitly silenced.
 > In the face of ambiguity, refuse the temptation to guess.
 > There should be one-- and preferably only one --obvious way to do it.
 > Although that way may not be obvious at first unless you're Dutch.
 > Now is better than never.
 > Although never is often better than *right* now.
 > If the implementation is hard to explain, it's a bad idea.
 > If the implementation is easy to explain, it may be a good idea.
 > Namespaces are one honking great idea -- let's do more of those!

## Wabi Sabi
The ideals of wabi-sabi come from Japan and the origins are based on keen observations of nature. By really seeing natural beauty for what it was, the Japanese were able to derive key ideals and concepts that are hard to explain in words and need to be experienced and felt to be best understood.

From this, follows [7 aesthetic principles](http://www.presentationzen.com/presentationzen/2009/09/exposing-ourselves-to-traditional-japanese-aesthetic-ideas-notions-that-may-seem-quite-foreign-to-most-of-us-is-a-goo.html):

 * *Simplicity* or elimination of the non-essential. Things are expressed in a plain, simple, natural manner.
 * *Asymmetry* or irregularity. Nature itself is full of beauty and harmonious relationships that are asymmetrical yet balanced. This is a dynamic beauty that attracts and engages.
 * Beautiful by being understated, or by being precisely what it was meant to be and not elaborated upon. *Direct* and simple way, without being flashy. Elegant simplicity, articulate brevity.
 * *Naturalness*. Absence of pretense or artificiality, show explicit, but unforced, intention. This is a reminder that design is not an accident.
 * Profundity or suggestion rather than revelation. That is, *showing more by showing less*.
 * Freedom from habit or formula. *Transcending the conventional*. This principles describes the feeling of surprise and a bit of amazement when one realizes they can have freedom from the conventional.
 * Tranquility or an energized calm (quite), *stillness*, solitude. This is related to the feeling of active calm and is the opposite feeling expressed by noise and disturbance.
