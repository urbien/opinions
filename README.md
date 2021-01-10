## Risk points for apps
We just saw [Parler app being suspended or banned](https://www.nytimes.com/2021/01/09/technology/apple-google-parler.html) from the app stores by Apple and Google, and by Amazon AWS cloud, for the user-produced content inciting violence. 

Putting aside the legal right of these platforms for such banning, every startup CEO needs has a duty to its shareholders to ask this question: what choke points exist on the Internet today that can be used against my app, whatever the intention could be, whether it is social issues, religious, political, anti-competitive, government imposed censorship, or any other.

## Choke points
Please help me identify them, but here are those that I know of:

1. **App Stores**. App Stores are notorious for blocking apps, 
and Apple has come under the scrutiny of the regulators in 2020 for doing that.
1. **Cloud providers**. In January 2021 Amazon AWS banned Parler from its cloud services.
1. **Domain registrars**. 
1. **DNS servers infrastructure**. The defense against this could be to use [ENS](https://ens.domains/), or to avoid using DNS and switch to DHT altogether (not an option for most apps).
1. **Certificate authorities**. Certificate Authority can revoke app's TLS / SSL certificate.
1. **Payment providers**. Wikileaks was denied banking services and the only way it was able to survive was the Bitcoin. 
In January 2021, Stripe [stopped processing payments for Trump Campaign](https://www.wsj.com/articles/stripe-stops-processing-payments-for-trump-campaign-website-11610319116). In January 2021, DLive was pressured by Tipalti, a payment company that helps it operate. 
Tilpati said in a statement that it had suspended its service until DLive removed the accounts that had broadcast the Capitol riots.
1. **Search engine**. Google was fined by EU for placing its own apps above competition in search results. If you app can't found on the Internet, it will have to rely on the word-of-mouth only. 
    1. App Stores have their own search engines and placing the app lower in search results can be easily used by them as a way to hurt the app's distribution.
1. **Ad networks**. Similarly to search engines, if the app can't advertise, its distribution is limited.
1. **CDNs**. Content Delivery Networks are often used to speed up downloading of content by users. 
Unfortunately CDN industry is quite concentrated in the handful of hands, like Akamai, Cloudflare, Fastly, etc. 
CDNs are not unavoidable, but not using them creates a worse customer experience.
1. **Platforms**. Varios platforms can block (de-platform) the app. There are so many of them, but to list a few:
    1. Push Notifications. Most apps rely on push notifications. There are only two services (by Google and Apple) that every app must use. No alternatives.
    1. Marketplaces. Amazon ecommerce marketplace, e-Bay, Shopify, Spotify and many others can block the app.
    1. Any Web API used by the app is potentially a choke point.
    1. Social media. Facebook, Twitter are infamous for blocking the apps that competed with their own services. Youtube, LinkedIn and all others have a similar power and they exercise it.
1. **ISPs**. This is the last line of attack, efficiently used today by the states that impose censorship. 
China instituted the first whole-country filtering service, that examines and blocks sites and content. 
A number of other countries followed. Usually VPN can effectively overcome this problem, but in China, 
VPN apps were ordered to be removed from the app stores, and the VPN servers are actively monitored, 
blocked or drastically slowed down by ISPs.

## Attack angles
Although not choke points, the attacks can be executed in different ways. 
1. Denial of Service attacks flooding app's systems can be fairly easily orchestrated.
1. The state can add a company producing the app to the grey / black lists, 
which would require anyone dealing with it to get a special permission from the government. 
This was used by Trump administration against Huawei, ZTE, and many others.
1. Suppliers and customers can be subverted, or influenced in some way or another. 
This is the method Trump administration used by forcing Google to deny Android license to Huawei. 
1. Offices can be raided and servers confiscated.
1. Prosecution.
1. ??? anything I missed?
