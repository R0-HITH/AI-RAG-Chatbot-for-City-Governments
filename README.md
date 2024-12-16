***Urban-Brain***

***Generative AI Retrieval-Augmented Generation (RAG) Chatbot Prototype for City Governments***

**Overview**

This repository contains the code and documentation for a Generative AI Retrieval-Augmented Generation (RAG) chatbot prototype developed for the City of Virginia Beach Government. The chatbot aims to improve citizen engagement and streamline access to city services by integrating advanced AI technologies with AWS services.

**Project Structure**

**Problem Definition**
Generative AI Retrieval-Augmented Generation (RAG) chatbots represent a significant advancement in the field of artificial intelligence. By combining the strengths of generative models and retrieval-based systems, RAG chatbots provide accurate, timely, and contextually relevant responses to user queries. This project addresses challenges such as information accessibility, timely updates, and efficient query handling for city government services.

**Datasets**
The City of Virginia Beach government website (https://virginiabeach.gov/) serves as the primary data source for this project. The website contains essential information such as public policies, community announcements, events, permits, and city service updates, which are indexed and retrieved by the chatbot to answer citizen inquiries effectively.

**Implementation**
The chatbot development process focuses on integrating key AWS services with advanced Generative AI models:

*Amazon Bedrock:* Integrates the Anthropic Claude LLM for conversational AI.
*Amazon Kendra:* Crawls and indexes the City of Virginia Beach website to provide relevant search-based content.
*Amazon Lambda:* Facilitates serverless backend operations for processing user queries.
*Amazon S3:* Secure storage for crawled data and chatbot configurations.
*Amazon Cognito:* Ensures user authentication and access control.
The implementation also includes prompt engineering and iterative testing to optimize performance.

**Testing**
The chatbot was tested through manual evaluation across multiple categories:

*Functional Testing:* Validated the chatbot’s ability to provide accurate responses to over 200 city-related queries.
*Error Handling Testing:* Assessed how well the chatbot managed queries with typos or incomplete information.
*Response Quality Testing:* Evaluated the chatbot's accuracy, confidence, and relevance when handling diverse inquiries.
*User Feedback Testing:* Implemented a feedback system for thumbs-up/thumbs-down ratings to identify areas for improvement.

**Findings**
The chatbot successfully demonstrated its ability to deliver:

Accurate and contextually relevant responses for straightforward queries.
Effective handling of paraphrased and reformulated questions.
Limited ability to manage multi-turn conversations and ambiguous inputs, indicating areas for future improvement.

**Summary**
This project establishes a scalable and secure Generative AI RAG chatbot that enhances communication between city governments and citizens. By integrating AWS tools and Anthropic Claude LLM, the chatbot delivers timely, accurate, and user-friendly responses, improving public access to essential city services.

**Future Work**
Multi-Language Support:
Implement Amazon Translate to enable support for Spanish, Tagalog, Vietnamese, Korean, and Arabic languages.
Integration with Other Models:
Explore integration with Meta LLaMA 90B Vision Instruct to enable image-based query processing.
Fine-Tuning Capabilities:
Investigate models that support fine-tuning to customize chatbot performance for local terminology and specific city service requirements.

## AWS Services Used

- **Amazon S3**: Storage for dataset and chatbot-related files.
- **Amazon Q&A bot**: Handles user interactions and processes queries.
- **Amazon Kendra**: Provides intelligent search capabilities.
- **Amazon Bedrock**: Utilizes high-performing foundation language models (LLMs).
- **AWS Lambda**: Facilitates serverless computing functions.
- **Amazon Cognito**: Manages user authentication and security.

