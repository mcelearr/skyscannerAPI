# Skyscanner API Challenge

## The Challenge
http://en.business.skyscanner.net/buildwithskyscanner

We are challenging all start-ups, developers  and aspiring entrepreneurs to build a game-changing new travel search website or app using our powerful Travel APIs.

The winner, who we think has built the most promising and innovative new product, will win the chance to spend one week working in Skyscanner’s office HQ, be coached by our very own Founder and CEO Gareth and receive a £1000 cash prize.
### I want to start building! How do I start?
First, sign up for and create an on-demand API key by using our login area here.

http://ww2.business.skyscanner.net/en-gb/accounts/login/?_ga=1.9218165.1326971205.1459456786

Make sure to come back to this page and fill in your email address in the box below to enter. Make sure you use the same email address you used to sign up to your API key.

You’ll have until 01 October 2016 to build your product. We’ll send you some helpful hints, tips and guides along the way.

Get involved with our team on Twitter @Skyscannertools, and tell us about your progress along the way using hashtag #BuildwithSkyscanner.

Winning team (up to 2 people) will get to come to office for 5 day week

Skyscanner will pay travel expenses up to value of £500 for team of up to 2

## Skyscanner API overview
http://business.skyscanner.net/portal/en-GB/Documentation/ApiOverview

http://en.business.skyscanner.net/en-gb/products/travel-apis/


### Cheapest Quotes

The Browse Quotes Service provides an aggregated view of flight and price data for many origins or many destinations over many time frames, returning the cheapest quotes where available. The prices returned are the cheapest price per day from our cache data.
Query Types

The query types are:

* Country to Anywhere (which other countries can be reached from the supplied country)
* City to Anywhere (which countries can be reached from the supplied city)
* Airport to Anywhere (which countries can be reached from the supplied airport)
* Country to Country (which destination airports are available from the origin country)
* City to Country (which destinations within the country are available from the given city)
* Airport to Country (which destinations within the country are available from the given airport)
* Country to City (and the reverse)
* Country to Airport (and the reverse)
* City to City Anytime (which months have prices in the next year)
* City to City Month (which days have prices in the specified months)
* City to City Day (prices for specified days)
* Airport to Airport Anytime (which months have prices in the next year)
* Airport to Airport Month (which days have prices in the specified months)
* Airport to Airport Day (prices for specified days)

Examples of questions that can be answered are:

* Find me the cheapest price for each available route from London to France for the next year. This gives the cheapest known price for each airport in France.
* Find me the cheapest price for each available route from London to anywhere departing in January and returning in February. This gives the cheapest known price for each destination country that can be reached from London.
* Find me the cheapest prices from Edinburgh to London in the next year. This gives the cheapest known price for each month of the coming year.
* Find me the cheapest prices from Edinburgh to London departing in January and returning in February. This gives the cheapest prices for each day in the months on the query.
* Find me the cheapest prices from Edinburgh to London departing on 5th January and returning on 6th February. This gives the cheapest prices for these days.

The Browse Quotes Service returns the known quotes for the given search. It is designed to return the raw quotes and does not aggregate the quotes and construct valid return quotes from one way quotes. There will need to be an amount of processing on the client side to get meaningful results. The Browse Routes, Browse Grid and Browse Dates services perform this processing on the server but return just the aggregated cheapest prices and not the full quote details.
