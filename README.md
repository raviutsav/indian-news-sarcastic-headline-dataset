I've established this database to address the scarcity of high-quality datasets featuring sarcastic news headlines within an Indian context. While other datasets exist, they are predominantly sourced from social media platforms. However, these sources often provide informal content, and the text is frequently extracted from comment replies, lacking comprehensive context.
<br>
Therefore, I aim to bridge this gap by providing a more structured and reliable dataset. In pursuit of this goal, I identified two primary sources renowned for their satirical news headlines in India:
<ul>
<li>The Fauxy</li>
<li>The Unreal Times</li>
</ul>
Scraping headlines from The Fauxy website proved relatively straightforward. However, accessing headlines from The Unreal Times posed a challenge due to its closure in November 2016. To circumvent this obstacle, I utilized the Wayback Machine to extract headlines from archived snapshots. It's worth noting that Archive.org imposes rate limits on Wayback Machine requests, necessitating the implementation of sleep timers between each request to fetch the site.

Despite these hurdles, I successfully amassed a total of 2128 headlines from The Fauxy and 1919 headlines from The Unreal Times, resulting in a combined dataset of 4047 entries.
