## 🔍 What is Website Spell Checker?

Website Spell Checker is a tool designed to **review the spelling and grammar of your entire website**. With the help of AI, this tool crawls through your website, identifies errors, and provides a detailed improvement report, ensuring your content is professional and error-free.

## 🕵️‍♂️ What can you do with this Website Spell Checker?

**📝 Automatically check spelling and grammar errors** across your website

🌐 Spell check a **website of any size** by setting customizable crawling levels

🔖 **Receive comprehensive reports** with URLs containing spelling errors, incorrect sentences, severity level of mistakes, corrected versions, and explanations

🔗 Integrate with your existing workflows using **API** and automate regular spelling checks

📥 **Download reports** in multiple formats, including JSON, CSV, XML, Excel, or HTML table

## 💸 Is this Webpage Spell Checker free?

You can try it for free with the $5 free usage credits every month on the [Apify Free plan](https://apify.com/pricing), allowing you to **run the Website Spell Checker within those limits**. The general cost of using this Actor is based on two factors:

1. **OpenAI API usage**: the number of API calls made to OpenAI for content analysis, based on OpenAI's current pricing structure.
2. **Apify Platform usage**: cost of crawling your website, determined by the number of pages crawled and the Actor's runtime.

For more extensive usage, consider getting an Apify subscription. We recommend our [$49/month Starter plan](https://apify.com/pricing) for regular website checks. For more detailed pricing information, please refer to [Apify Pricing](https://apify.com/pricing) and [OpenAI Pricing](https://www.notion.so/OpenAI-5e281c6e929a4b8a98a13bd02b0d1f01?pvs=21).

## 🚀 How to use Website Spell Checker to do spell check in page

It's easy to ensure your website is error-free with Website Spell Checker. Just follow these steps:

1. Find [Website Spell Checker](https://apify.com/oscardz/website-spell-checker) on Apify Store and click the **Try for free** button.
2. Input website URL to start with.
3. Add your Open AI API key.
4. Set any optional parameters like number of pages to scan, crawling depth or high-severity errors only option.
5. Click “Start” button.
6. Review the generated report to see all identified spelling and grammar issues.
7. Export your error report in JSON, XML, CSV, Excel, or HTML or using an API.

## ⬇️ Input

To check your website for spelling and grammar errors, simply input the **website URL and add your Open AI API key**. You can input the data manually or programmatically via an API. For more details on how to configure input, see the [input tab](https://apify.com/oscardz/website-spell-checker/input-schema).

## ⬆️ Output sample

The results will be compiled into a comprehensive report available in the **Output** tab. The report will include the URLs where the error was found, the incorrect sentences, the corrected versions, and explanations for each error. You can choose the format in which to export this data: JSON, CSV, Excel, or HTML.

Here’s a sample spell check report in JSON format:

```json
[
  {
    "URL": "https://example.com/about",
    "sentence_mistake": "Our company is commited to excellence.",
    "sentence_corrected": "Our company is committed to excellence.",
    "explanation": "The word 'commited' is misspelled; the correct spelling is 'committed'."
    "severity": "high"
  },
  {
    "URL": "https://example.com/contact",
    "sentence_mistake": "Feel free to reach out to us if you have any querries.",
    "sentence_corrected": "Feel free to reach out to us if you have any queries.",
    "explanation": "The word 'querries' is misspelled; the correct spelling is 'queries'."
    "severity": "high"
  },
   {
	  "URL": "https://example.com/anouncement",
    "sentence_mistake": "All in favour to our community and highlighting the amazing tools you create!",
    "sentence_corrected": "All in favor of our community and highlighting the amazing tools you create!",
    "explanation": "The phrase 'in favour to' is incorrect; it should be 'in favor of' to indicate support or approval.",
    "severity": "medium"
          },
]
```

## ❓ FAQ

### How does this Website Spell Checker work?

The tool crawls your website, scanning each page for spelling and grammar errors. It then connects to ChatGPT to review and explain found errors. Lastly, this URL spell checker compiles these errors into a report, offering suggestions for corrections.

### Can I use Website Spell Checker as an API?

Yes, you can use the Apify API to integrate Website Spell Checker into your existing workflows. The API allows you to manage, schedule, and run Apify Actors, access data you've extracted, monitor performance, retrieve results, create and update Actor versions, and more.

To access the API with Node.js or Python, you can use the `apify-client` via the [NPM package](https://apify.com/oscardz/website-spell-checker/api/client/nodejs) or the [PyPI package](https://apify.com/oscardz/website-spell-checker/api/client/python). Alternatively, there are [API endpoints](https://apify.com/oscardz/website-spell-checker/api/endpoints) available for extracting data directly. For detailed information and code examples, check the [API tab](https://apify.com/oscardz/website-spell-checker/api/client/nodejs) or refer to the [Apify API documentation](https://docs.apify.com/api/v2).

### Can I integrate Website Spell Checker with other apps?

Yes, Website Spell Checker can be integrated with most cloud services or web apps using Apify’s integration options. You can [connect your data](https://apify.com/integrations) with platforms like Zapier, Slack, Make, Airbyte, GitHub, Google Drive, LangChain, and more.

You can also use [webhooks](https://docs.apify.com/integrations/webhooks) to perform actions based on specific events, such as receiving a notification when the Website Spell Checker successfully completes a run.

### Website Spelling Checker isn't working correctly. How do I get support?

We’re always working on creating the best Website Spell Checker. So if you’ve got any issues, questions, or feature requests for this Website Spelling Checker or simply found a bug, please add an issue to the Actor’s [Issues tab](https://apify.com/oscardz/website-spell-checker/issues/open). We’re here to help!