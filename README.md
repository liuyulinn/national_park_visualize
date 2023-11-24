A visualize tool for National Parks in USA. 

# Usage

1. You need first obtain your Google Map API key and then replace YOUR_API_KEY in the two html file by your key.
2. Open the html file.

rank.html: show the ranking of each national parks, by click on icon, you will get more information of this park.

score.html: the size of the icon shows the scenary of this park (the larger the better), and the color indicates the overall score of this park (considering accessibility, recreation, crowds, amenities, scenery). By click on icon, you will get more information of this park.

# Sources

The score, rank are brought from [https://morethanjustparks.com/national-parks-ranked/](https://morethanjustparks.com/national-parks-ranked/)

For more information, you can search [https://morethanjustparks.com](https://morethanjustparks.com)

# How to obtain A Google Map API Key?

Brought from ChatGPT 3.5:

To obtain a Google Maps API key, you need to follow these steps:

1. **Go to the Google Cloud Platform Console:** Visit the [Google Cloud Platform Console](https://console.cloud.google.com/).
2. **Create a Project (if needed):** If you don’t have a project, you’ll need to create one. Click on the project dropdown at the top left of the page and select "New Project."
3. **Enable the Maps JavaScript API:** In the Google Cloud Platform Console, select your project, then navigate to the "APIs & Services" → "Library" section from the left-hand sidebar. Search for "Maps JavaScript API" and click on it. Click the "Enable" button.
4. **Create API Key:** Once the Maps JavaScript API is enabled, go to the "APIs & Services" → "Credentials" section from the left-hand sidebar. Click on the "Create Credentials" button and select "API key." You'll get your API key.
5. **Restrict Usage (Optional but Recommended):** For security, it's wise to restrict the usage of your API key. You can set restrictions based on HTTP referrers (websites), IP addresses, or app restrictions (if applicable). This helps prevent unauthorized usage of your key.
6. **Use the API Key:** Once you have the API key, you can use it in your code by adding it as a parameter in the API requests, as shown in the examples provided earlier.

Keep in mind that while using the Google Maps API, especially in a production environment or for high-traffic usage, you may encounter billing aspects. Google provides a certain amount of free usage per month, and beyond that, charges may apply. Always check the [Google Maps Platform Pricing](https://cloud.google.com/maps-platform/pricing) to understand the pricing structure and usage limits.

Remember to keep your API key secure and never share it publicly, especially in client-side code (like JavaScript in web pages) as it could be abused. Use secure practices such as restricting API key usage and implementing proper security measures.
