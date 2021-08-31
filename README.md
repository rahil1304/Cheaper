## :money_with_wings: cheaper
An upcoming chrome extension and API that scrapes the most popular e-commerce websites to get the best deals on the searched query across these websites.

#### What does cheaper do?
Pass any search string to the cheaper API. It can be called by the following command
<pre><code>
    cheaper 'Philips Hue Bulb'
</code></pre>

The API returns the prices for the searched items from e-commerce websites in a JSON object

<pre><code>
    {
        id: 1630436269,
        website: 'AMZ',
        searchedString: 'Philips Hue Bulb',
        results: [
            {
                title: 'Philips Hue White A21 High Lumen Smart Bulb, 1600 Lumens, Bluetooth & Zigbee compatible (Hue Hub Optional), Works with Alexa & Google Assistant',
                price: 19.99,
                currency: 'USD',
                ...
            }
        ],
        ...
    }
</code></pre>