# **TaxEaseAI : Vertex AI Agent 🤖**

![TaxEaseAI Banner](assets/banner.png)

## **Description 🎃**

**TaxEaseAI** is a user-friendly AI assistant designed to demystify and simplify US tax filing, a system that has become needlessly convoluted and stressful for millions of Americans.

Built on the powerful Vertex AI platform, TaxEaseAI utilizes a comprehensive knowledge base within Datastore, containing up-to-date tax forms, instructions, FAQs, and more. Seamless communication via OpenAPI and a sophisticated Retrieval Augmented Generation (RAG) approach ensure that TaxEaseAI provides accurate, personalized, and easy-to-understand guidance throughout the entire tax filing process.

## **Inspiration ✨**

Our inspiration for **TaxEaseAI** stemmed from a deep empathy for the millions of Americans who dread the annual ritual of tax filing. Emmy-winning journalist Johnny Harris eloquently captured this sentiment in his video essay,  "[*Why Americans Pay to Do Their Taxes?*](https://www.youtube.com/watch?v=ZhV4Z76mXrI)". Harris exposed the absurdity of a system that forces its citizens to navigate a labyrinth of complex forms and expensive software, all while simpler, government-run solutions exist in numerous other countries.

We've all felt the frustration – the hours wasted deciphering cryptic forms, the fear of missing a crucial deduction, the sinking feeling when you realize you need to shell out for expensive tax software. TaxEaseAI aims to simplify this process and empower users with an intelligent tax assistant that makes tax filing straightforward and stress-free.

## **What it does 💡**

TaxEaseAI is a user-friendly AI assistant designed to demystify and simplify US tax filing. Here's how it works:

* **Direct Form Filling:** Already know the forms you need? TaxEaseAI acts as your smart assistant, guiding you through the process and answering your questions in real-time.
* **Interactive Guidance:** Not sure where to start? TaxEaseAI engages in a friendly Q&A to understand your unique situation. It then recommends relevant forms, identifies potential deductions, and helps you avoid costly errors.

## **How we built it 🧐**

* **Vertex AI:** Our entire application is built on the powerful Vertex AI platform, using its agent as the brain of our system to understand requests and manage interactions.
* **Datastore:** We've created a comprehensive knowledge base within Datastore, storing all the latest tax forms, instructions, FAQs, and more. This ensures TaxEaseAI always has the most up-to-date information.
* **OpenAPI:** Seamless communication is key! We integrated OpenAPI to allow our AI agent to smoothly retrieve and process data from Datastore.
* **RAG Approach:** We implemented a Retrieval Augmented Generation (RAG) approach. This means TaxEaseAI doesn't just spit out generic answers; it retrieves relevant information and crafts personalized responses just for you.

## **Challenges we ran into 🛇**

* **Accuracy & Compliance:** Taxes are serious business! We worked hard to build in robust validation checks and ensure our system adheres to IRS guidelines.
* **Tax Code Complexity:** The US tax code is complex. Building an AI system capable of understanding and navigating its intricacies was a major challenge!
* **User-Friendliness:** We prioritized designing a clean, intuitive, and approachable user experience for everyone.

## **Accomplishments that we're proud of 🎉**

* **Functional AI Tax Assistant:** We built a working prototype that showcases the power of AI to simplify taxes.
* **User-Centric Design:** TaxEaseAI is designed with you in mind, focusing on making the experience as smooth and painless as possible.
* **Equity in Action:** We believe TaxEaseAI has the potential to make tax filing less intimidating and more accessible for all, regardless of income or technical expertise.

## **What we learned 📚**

* **The Power of Vertex AI:** This project gave us invaluable experience with Vertex AI's incredible capabilities, solidifying our understanding of intelligent agent development.
* **User-First, Always:** When dealing with complex topics like taxes, simple and clear design is paramount.
* **AI for Good:** This project reinforced our belief in the power of AI to create positive change and address real-world problems.

## **What's next for TaxEaseAI 🚀**

* **Expand Functionality:** We envision integrating with financial platforms, enabling automatic form population from user data, and offering advanced features for more complex tax scenarios.
* **Testing & Refinement:** We'll be conducting thorough testing with real users to gather feedback and make TaxEaseAI even more accurate and user-friendly.
* **Advocacy for Change:** We plan to use TaxEaseAI to raise awareness about the need for a simpler, fairer, and more transparent US tax system.

## **Test Script 🖊️**

* What will be my tax rate if my income is about 65000 USD, Single?
* What is Section 951(a) inclusion?
* What are 'Standard deduction or itemized deductions' from Schedule A?

## **Setup** ⚙️

### **Diagflow CX Side Panel**

```html
<link rel="stylesheet" href="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/themes/df-messenger-default.css">
<script src="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/df-messenger.js"></script>
<df-messenger location="northamerica-northeast1" project-id="taxeaseai" agent-id="8fd37925-c76a-47e1-b574-25802ef23665" language-code="en" max-query-length="-1">
  <df-messenger-chat chat-title="TaxEaseAI Assistant"></df-messenger-chat>
</df-messenger>
<style>
  df-messenger {
    z-index: 999;
    position: fixed;
    --df-messenger-font-family: Google Sans;
    --df-messenger-chat-background: #1d1d1d;
    --df-messenger-message-user-background: #e9e9b1;
    --df-messenger-message-bot-background: #3c6255;
    --df-messenger-message-bot-font-color: #fff;
    --df-messenger-message-user-font-color: #000000;
    bottom: 0;
    right: 0;
    top: 0;
    width: 350px;
  }
</style>
```

## **Repository Link 🔗**

[GitHub Repository](https://github.com/AnuragRaut08/TaxEaseAI.git)

