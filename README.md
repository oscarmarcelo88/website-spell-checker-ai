## 🔍 What is Website Spell Checker?

Website Spell Checker is a tool designed to **review the spelling and grammar of your entire website**. Using AI, it crawls through your site, identifies errors, and provides a detailed improvement report to keep your content professional and error-free.

You can **scale this tool to check hundreds or even thousands of pages**, and connect it through Apify’s API to integrate automatic spell-checking into your workflow.

## 🕵️‍♂️ What can you do with this Website Spell Checker?

**📝 Automatically check spelling and grammar errors** across your website

🌐 Spell check a **website of any size** by setting customizable crawling levels

🔖 **Receive comprehensive reports** with URLs containing spelling errors, incorrect sentences, severity level of mistakes, corrected versions, and explanations

🔗 Integrate with your existing workflows using **API** and automate regular spelling checks

📥 **Download reports** in multiple formats, including JSON, CSV, XML, Excel, or HTML table

## 💸 Cost of using the Webpage Spell Checker

You can try the Webpage Spell Checker for free with Apify’s $5 monthly usage credit on the [Free plan](https://apify.com/pricing). The cost of using this actor depends on Apify platform usage alone. Typically, **it costs just a few dollars to check hundreds of pages.**



## ⬆️ Output sample

The results will be compiled into a comprehensive report available in the **Output** tab. The report will include the URLs where the error was found, the incorrect sentences, the corrected versions, and explanations for each error. You can choose the format in which to export this data: JSON, CSV, Excel, or HTML.

Here’s a sample spell check report in JSON format:

```json
[
  {
    "URL": "https://example.com/about",
    "sentence_mistake": "Our company is commited to excellence.",
    "sentence_corrected": "Our company is committed to excellence.",
    "explanation": "The word 'commited' is misspelled; the correct spelling is 'committed'.",
    "severity": "high"
  },
  {
    "URL": "https://example.com/contact",
    "sentence_mistake": "Feel free to reach out to us if you have any querries.",
    "sentence_corrected": "Feel free to reach out to us if you have any queries.",
    "explanation": "The word 'querries' is misspelled; the correct spelling is 'queries'.",
    "severity": "high"
  },
  {
    "URL": "https://example.com/anouncement",
    "sentence_mistake": "All in favour to our community and highlighting the amazing tools you create!",
    "sentence_corrected": "All in favor of our community and highlighting the amazing tools you create!",
    "explanation": "The phrase 'in favour to' is incorrect; it should be 'in favor of' to indicate support or approval.",
    "severity": "medium"
  }
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