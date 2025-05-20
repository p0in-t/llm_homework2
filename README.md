# Smart Translator

A Python-based translation tool that uses LangChain, Google's Gemini API, and web search capabilities to provide accurate translations with cultural context.<br/><br/>
Features:
<br/>

Automatic language detection<br/>
Translation between multiple languages<br/>
Verification of cultural references and technical terms using web search<br/>
Handling of idiomatic expressions<br/>

Requirements:<br/>
langchain<br/>
langchain_openai<br/>
langchain_google_genai<br/>
langchain_community<br/>
tavily-python<br/>
numpy<br/>

Setup:<br/>

Install dependencies:<br/>
pip install langchain langchain_openai langchain_google_genai langchain_community tavily-python numpy<br/>

Set API keys in the script or as environment variables:<br/>

Replace YOUR_GOOGLE_API_KEY with your Google API key<br/>
Replace YOUR_TAVILY_API_KEY with your Tavily API key<br/>

Usage:<br/>
Run the script:<br/>
Enter translation requests at the prompt:<br/>
Translate to English: Hola, ¿cómo estás?<br/>
Type quit, exit, or q to exit the application.<br/><br/>
How It Works:<br/>

Detects source and target languages from the user query<br/>
Performs initial translation using Google Gemini model<br/>
Verifies translation accuracy using web search when needed for cultural contexts<br/>
Returns enhanced translation with proper context for culturally specific terms<br/>
