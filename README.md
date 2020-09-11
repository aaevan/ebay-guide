# ebay-guide

So, you want to buy something! Ebay is great but it can be a little tricky finding exactly the thing you want, especially if you're used to shinier more curated marketplaces like Amazon. Ebay sells everything from brand new cars to obscure & out of production machine parts. With a bit of patience and effort, you can find some incredible deals.

As an example item, we'll use one of my favorite objects: **Shure SE215 sound isolating earphones** Two years later, I'm still the pair I got used on ebay (for roughly half or retail).

A few questions to start our search:

* Is authenticity a concern (any name-brand electronics or small high value items)?
  * Unless it's something obscure or high value, we probably want to buy from the US. (I'm assuming a US audience)
  * Make sure to buy from a reputable seller. Check out their seller rating: basically anything under 99% is sketchy.
* Ask, am I willing to wait up to a month and a half for it to get here?
  * If so, it might make sense to buy direct from china through ebay listings or something like aliexpress.
    * Aliexpress has a particularly messy and unpredictable search function so don't try to use any fancy operators like you'll see below.
    * If you're buying small quantities of electronics or machine parts that aren't system critical, Aliexpress is for you. (Arduino clones for $2? yes please.)
  * If you're not willing to wait that long, under **Item Location**, make sure to check the box that says, North America. 
    * generally, ordering something from somewhere from the continental US will take a week or two *max* to get to you.

* How much does your item generally sell for?
  * To get an upper bound, check Amazon and a few other retailers. Amazon tends to be 10 to 20% more expensive than the best deal on ebay. (*citation needed*)
  * For the lower bound, check the "sold listings" box and sort by "Price + Shipping: lowest first".

Okay, so we now have an upper and lower bound on the price of the item (SE215: $99 new from amazon, roughly $30, shipping included from ebay). Time to start searching.

# A basic search:

To start, in the search bar type in the shortest unique string in your product name (found via Amazon etc.). Amazon is evil but it's totally valid to use it as a directory.

In our example case, there's pretty much only one object with the string "SE215" in it, so we can trim our query down to that.

> se215

Ebay doesn't care about capitalization. If a word in your search string is close to a common word, it might try to autocorrect your string to a dictionary word. Put quotes around your search to be sure that exact string appears in the listing title.

> "se215"

Are you willing to buy a used item? If so, on the sidebar under **Condition**, click, "see all" and check everything that isn't new. "New" items are likely to be close in price to retail and, we want a good deal, so we'll start by ignoring everything that is "new". Also, we want something that *works*, save some time and don't check "For parts or not working".

- [ ] New
- [X] Open Box
- [X] Seller Refurbished
- [X] Used
- [ ] For parts or not working

*note: It's not applicable for this search, but for some items, the actual manufacturer will sell factory refurbished items at a steep discount. Worth checking out.*

The shorter the query, the more noise you're going to get. Scan down the page and if you see an object repeated (say, a travel case or some totally unrelated class of objects), add a minus clause to your search. In our example, we want a complete set (earbuds, cable and case) so let's cull all listings with the string "no cable".

> se215 -"no cable"

Okay, so now we should have quite a few options. If you need it soon, and you're willing to pay a small premium (still probably cheaper than amazon), along the top, just below the search bar, click the "Buy it Now" tab. Sorted by "Price + Shipping: lowest first", you should have now a short list of candidates.

A rough gauge of how good of a deal something is is to look for the "*n* watched in last hour". If you see more than about 5 watchers on an item and it's a single count buy it now auction, chances are you're looking at a particularly good deal. If it's something from china or if it has fancy glossy product photos and it has a high watcher count, you're probably looking at a artificially created watcher count.

If you're buying something kinda obscure, you might only get 2 or 3 active listings, but that's what the "Save this search" button is for (see below).

If it's substantially cheaper than surrounding listings (especially for buy it now listings), there's a small chance that the seller is pulling some kind of scam. I've only had this happen to me maybe twice in my hundreds of ebay purchases but it's worth watching out for. If it's "buy it now" for $20 cheaper than its competition and you're baffled how they could ship something for that much, it's probably too good to be true. That said, occasionally someone will sell factory seconds of something for a greatly reduced price, so don't automatically discount a low price.

For each listing, read the description closely and look at each photo. Most of the time, the seller will have a 1-2 line blurb about the condition of the item.

If the seller says it works, and it doesn't work, Ebay has a really good return policy and they'll make the seller pay the return shipping. They'll accept a return for a nonfunctional item even if the seller "does not accept returns". This is relatively uncommon but still worth remembering.

Caveat for medium sized to large items: keep an eye out for "local pickup only". This means, "literally drive to the seller's house and cart it away. It's sad because sometimes you'll see something for 20% or more less than every other item but it's "local pickup only" in rural Nebraska. Most of the time the seller is clear on that, but very occasionally they'll say "free shipping" or provide a wild estimate but actually inclue the full shipping terms in the item description.

If you're buying a common consumer good (toothpaste for example), there's a good chance the results you see will include dropshipped items from Amazon, Walmart or another major retailer. It probably violates the TOS somewhere, but the seller will paste your name and address into the shipping info and the item will be sent to you. Occasionally, I'll receive an amazon package in the mail, be briefly confused, then realize that's what's happening. The seller makes an extra dollar or two (on top of the Prime price of the item) and you'll get questionably ethical free shipping.

# Auctions:

If you're willing to be patient, auctions consistently have better prices than **Buy It Now** listings but it comes at the cost of scheduling 10m out of your life to stare at the last few minutes of a listing. Bids made before the last minute or two are basically meaningless for low value items. If you're buying a car on ebay, then, this isn't the guide for you.

The basic idea is, as close to the end of the auction as possible (about 5-10s within the end of bidding), place a bid that is the maximum value you'd be willing to pay, followed by a semi-random cents value. If your max purchase price is $50, it's likely that someone else's max is around there too. Throw some noise on the end of your number to increase your chances of winning the auction. A max bid of $51.73 is better than $50.00.

Often, if you bid slightly higher than your lower bound estimate within the last few seconds of a listing, you can get something for a ridiculously good deal.

Add things to your watchlist if you'd like to buy it in the future.

# The "Bottom up" method:

So, say you want to buy a common item, but it doesn't really matter exactly what model you get as long as it's decent quality. Let's use a usb battery bank as an example:

> usb battery bank

This will return a lot of garbage listings. To start with, narrow down by location, condition and price. Next, do a ~~google~~ duckduckgo search a few "best class-of-item 2020" object lists. Wirecutter is generally pretty good starting place, but sometimes they aren't too thorough with their durability testing. If you see a brand dominate across two or more different lists, (in our case, let's say **Anker** and **Jackery**), let's add those brands to our search query. If there are multiple high quality brands in the same space, we can use an **OR** operator:
 
> usb battery bank '(anker, jackery)'

The syntax is, '(query1, query2, query3)', don't forget the commas. It might be tempting to use more than one **OR** in a search, but things start to get strange. Try to keep it to one or split your search into multiple saved searches.

You'll see immediately a whole bunch of things you don't want. After culling the largest number with the above methods (shipping from, condition, etc.) start weeding out extra listings aggressively using quoted minus operators. Try to pick a string that's unique to the listings you're culling:

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
