# ebay-guide

Ebay is great but it can be a little tricky finding the best deals, especially if you're used to shinier more curated marketplaces like Amazon. Ebay sells everything from brand new cars to obscure & out of production machine parts. With a bit of patience and effort, you can find some incredible deals.

As an example item, we'll use one of my favorite objects: **Shure SE215 sound isolating earphones** Two years later, I'm still using the pair I got used on ebay (for roughly half or retail).

A few questions to start our search:

* Is authenticity a concern (any name-brand electronics or small high value items)?
  * If it's something high value, we probably want to buy from the US or Canada. (I'm assuming a US audience)
  * Make sure to buy from a reputable seller. Check out their seller rating: basically anything under 99% is sketchy.
  * Be wary of new items sold by sellers with under about 50 transactions (the number next to the seller name).
* Ask, am I willing to wait up to a month and a half for it to get here?
  * If so, it might make sense to buy direct from china through ebay listings or something like aliexpress.
    * Aliexpress has a particularly messy and unpredictable search function so don't try to use any fancy operators like you'll see below.
    * If you're buying small quantities of electronics or machine parts that aren't system-critical, Aliexpress is for you.
    * Comparing prices between items on eBay shipped from china and those found on Aliexpress, Aliexpress tends to be marginally cheaper.
  * If you're not willing to wait that long, in the filter sidebar under **Item Location** (I'm assuming you're searching from a laptop), make sure to check the box that says, North America.
    * generally, ordering something from somewhere from the continental US will take a week or two *max* to get to you.
* How much does your item generally retail for?
  * To get an upper bound, check Amazon and a few other retailers. Amazon tends to be about 10 to 20% more expensive than the best deal on ebay.
  * For the lower bound, check the "sold listings" box and sort by "Price + Shipping: lowest first" and take a rough average of recent sales.

Okay, so we now have an upper and lower bound on the price of the item (SE215: $99 new from amazon, roughly $30, shipping included from ebay). Time to start searching.

# A basic search:

To start, in the search bar type in the shortest unique string in your product name (found via Amazon etc.). Amazon is evil but it's totally valid to use it as a directory. In our example case, there's pretty much only one object with the string "SE215" in it, so we can trim our query down to that.

`se215`

Ebay searches don't care about capitalization or word order. `se215 headphones` returns the same results as `headphones SE215`.

If you need it soon, and you're willing to pay a small premium, just below the search bar, click the "Buy it Now" button. Sorted by "Price + Shipping: lowest first".

If a word in your search string is close to a common word, it may try to autocorrect your string to a dictionary word. Put quotes around your search to be sure that exact string appears in the listing title.

`"se215"`

Are you willing to buy a used item? If so, on the sidebar under **Condition**, click, "see all" and check everything that isn't new. **New** items are likely to be close in price to retail, so we can start by ignoring everything that is "new". Also, we want something that *works*, so we'll save some time and leave "For parts or not working" unchecked:

- [ ] New
- [X] Open Box
- [X] Seller Refurbished
- [X] Used
- [ ] For parts or not working

*note: It's not applicable for this search, but for some items, the actual manufacturer will sell factory refurbished items at a steep discount. Worth checking out.*

The shorter the query, the more noise you're going to get. I like to iteratively filter out large chunks of the original results until it's just a few pages or results. Another useful technique is to add a minus clause to your search. In our example, we want a complete set (earbuds, cable and case) so let's filter out all listings with the string "no cable".

> se215 -"no cable"

Okay, so now we should have a much more manageable number of results. 

If a listing is getting a lot of traffic (either new watchers or many views), you'll see a red "*n* watched in last hour" or a "*n* watched in the last day" message. If you see a listing for a single lot that more than about 5 watchers on an item, there's a good chance that you're looking at a good deal. If it's something from china or if it has fancy glossy product photos and it has a high watcher count, you're probably looking at a artificially created watcher count.

If you're buying something kinda obscure, you might only get 2 or 3 active listings, but that's what the "Save this search" button is for (see below).

If it's substantially cheaper than surrounding listings (especially for buy it now listings), there's a small chance that the seller is pulling some kind of scam. I've only had this happen to me maybe twice in my hundreds of ebay purchases but it's worth watching out for. If it's "buy it now" for $20 cheaper than its competition and you're baffled how they could ship something for that much, it's probably too good to be true. That said, occasionally someone will sell factory seconds of something for a greatly reduced price, so don't automatically discount a low price.

For each listing, read the description closely and look at each photo. Most of the time, the seller will have a 1-2 line blurb about the condition of the item. 
If the seller says it works, and it doesn't work, Ebay has a really good return policy and they'll make the seller pay the return shipping. They'll accept a return for a nonfunctional item even if the seller "does not accept returns". This is relatively uncommon but still worth remembering.

Caveat for medium sized to large items: keep an eye out for "local pickup only". This means, "literally drive to the seller's house and cart it away. It can be frustrating because sometimes you'll see something for 20% or more less than every other item but it's "local pickup only" in rural Nebraska. Most of the time the seller is clear on that, but very occasionally they'll say "free shipping" or provide a wild estimate but actually inclue the full shipping terms in the item description. Be extra careful navigating shipping costs for large items. It might just say "freight" and that's almost guaranteed to be upsettingly expensive.

If you're buying a common consumer good (toothpaste for example), there's a good chance that you'll see dropshipped items from Amazon, Walmart or another major retailer. It probably violates the TOS somewhere, but the seller will paste your name and address into the shipping info and the item will be sent to you. Occasionally, I'll receive a surprise amazon package in the mail, be briefly confused, then realize that's what's happening. The seller makes an extra dollar or two (on top of the Prime price of the item) and you'll get questionably ethical free shipping.

# Auctions:

If you're willing to be patient, auctions consistently have better prices than **Buy It Now** listings but it comes at the cost of scheduling 10m out of your life to stare at the last few minutes of a listing. For relatively low value items, bids made before the last minute or two are basically meaningless. The rules are a little different for high value items and that's not something I have any experience with.

The basic idea is, find an item you'd be willing to buy that is currently at or below your desired price point. Especially for a listing with >10 watchers, you'll often see a flurry of bidding in the last few minutes-- don't even try to participate in that though. As close to the end of the auction as possible (i.e. within 5-10s of the end of the listing), place a bid that is the maximum value you'd be willing to pay, followed by a semi-random cents value. If your max purchase price is $50, it's likely that someone else's max is around there too. Throw some noise on the end of your number to increase your chances of winning the auction. A max bid of $51.73 is better than $50.00.

For a heavily watched item, there's a decent chance someone else is doing exactly the same thing (bidding in the last few seconds), so, it's a bit of a gamble whether you'll win the auction. If the price shoots way above your guess, update your guess and try again next time. At a vague guess, I'd say somewhere between 1 in 5 to 1 in 10 watchers will actually participate in the last minute bidding.

Add things to your watchlist if you'd consider buying it in the future.

Most of the time, when I'm buying low value items (under $30?) I'm willing to pay a few dollars to not go through this process. It's definitely worth your time for higher value items. If your item is a little obscure and there are not many watchers, you can often swoop in and win an auction with almost no competition.

# The "Bottom up" method:

Sometimes, it doesn't matter what model or brand you get. One of my favorite ways to use eBay is to start with an extremely general search and build up a query from a few things you do want and a bunch of things you don't want. For a given class of item, there's likely to be a few under-valued listings, it's just a matter of finding them. Let's use a usb battery bank as an example:

`usb battery bank` (23546 listings)

First, to make sure we're not missing any miscategorized items, in the top-most section of the left sidebar under **Categories**, select "All".

This will return a lot of garbage listings . To start with, narrow down by location, condition and price (9741 listings). Next, do a ~~google~~ duckduckgo search a few "best class-of-item 2020" object lists. Wirecutter is generally pretty good starting place, but sometimes they aren't too thorough with their durability testing. It's likely the "best" items from recent lists will have heavy competition, but if you don't need the very newest thing, you can sometimes look at a "best of" list from a few years back and find a totally acceptable solution at 2/3 or 1/2 the price. If you see a brand dominate across two or more "best of" lists, (in our case, let's say for example, **Anker** and **Jackery**), add those brands to our search query. If there are multiple high quality brands or common models, we can use an **OR** operator:

Filtered by condition:
`usb battery bank'`condition: **open box**, **seller refurbished** or **used** (359 results)

Filtered by condition and an **OR** clause:
`usb battery bank '(powercore, 20100, 20000, 26800)' condition: **open box**, **seller refurbished** or **used**` (11 results)

The syntax is, '(query1, query2, query3)', don't forget the commas. You can also **OR** together quoted strings (or a mix of quoted and unquoted strings), just be sure to use double quotes instead of single quotes inside the **OR** block's parentheses:

`usb battery bank '("powercore 20100", "powercore 20000")'`

It might be tempting to use more than one **OR** in a search, but things start to get strange. Try to keep it to one or split your search into multiple saved searches.

You'll see immediately a whole bunch of things you don't want. After culling the largest number with the above methods (shipping from, condition, etc.) start weeding out extra listings aggressively using quoted minus operators. Try to pick a string that's common to multiple listings you don't want to see:

> usb battery bank '(anker, jackery)' -5000 -10000 -mini

I only occasionally make search strings long enough that ebay complains. Go wild. If you only see a handful of results for your query, first try trimming away extra words to broaden your search. If the number of search results explodes, you probably got rid of a useful keyword. Go back and try again.

> usb battery '(anker, jackery)' -5000 -10000 -mini

Also, if you want get even more tedious, start with just the brand names you'd accept and cull away things that aren't what you want.

> '(anker, jackery)' -5000 -10000 -mini -flashlight -bluetooth -meister -vintage -sports -sport -watch -earbud -wireless

This query was a dead end but it's a good example of how long queries can get. Watch the results count and if you see it suddenly increase after a new minus clause that means you've hit some sort of invisible ceiling. Go back and try something more specific.

# Obscure or rare items:

Okay, so you've done all this and there's only two listings and they're each out of your price range? Time to save your search.

After saving a search, you'll get emails or push notifications (your choice) any time a new listing is created that matches your query.

When I've made a particularly ugly and long winded query, I'll remind myself what the query is for by including a minus clause at the beginning:

> -"CHEAP ANKER OR JACKERY" usb battery '(anker, jackery)' -5000 -10000 -mini

Because it's removing items that match the quoted query, you can put whatever you want in there. It's great.

If you're looking for something in a specific condition but your query returns nothing, there's a trick to creating a search alert for it. Ebay only displays condition types that are found within your current query. If a "used" item is not available, you can do a very general search (ex.: `drill`), toggle the appropriate boxes filtering by condition, then narrow the search again (ex.: `drill makita XPH07`). For now, you'll probably get zero results, but the filters from the more general search will carry over. You can now save this search and you'll get notified when something matches it.

# Laptop shopping:

Pick a few characteristics that you want and build up a bottom up query from there. I might start with something like:

> thinkpad i7 ssd 16gb

Don't like something? Trim it away:

> thinkpad i7 ssd 16gb -yoga

Next, trim off your results by your max budget and sort by "Price + Shipping: highest first".

The idea is to buy as much computer as you can within your budget. As a thought experiment, try halving your first budget and see if you find anything acceptable. $250 goes a long ways, especially if you're willing to do a bit of work yourself (especially, installing your own OS on a hard drive you buy separately). The past two computers I've bought (both thinkpads) were $115 and $240 respectively (shipped).

Try to go with a seller that accepts returns and avoid "as is"/"for parts or repair" listings.

Here, especially (for used computers), the watcher count ("5 watching") and views count ("5 per hour") is a particularly good indicator of a good deal. Sometimes if there are a high number of views but few watchers, that *might* be an indicator that there's something subtly wrong with the item listed ("small mark on screen").

# Comments/suggestions/typos:

I'm on twitter at @aoeb-- message me there or submit a pull request and I'll see about including your tip/technique (giving you full credit)!

I spend quite a lot of time on ebay so I figured I'd share what I've learned.

Long live cheap stuff from internet randos!
