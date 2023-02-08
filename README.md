# AI Search

Prototype of using [GPT-3](https://openai.com/api/) to answer and refine search results (provided by [DuckDuckGo](https://duckduckgo.com/)), build using [Node-RED](https://nodered.org/). This proof of concept is to show how companies like Microsoft and Alphabet can use a language model to provide users of Bing and Google with answer to their questions based on reliable and traceble information. Users can refine their questions or ask for more details in a context-aware way. All sources used to derive an answer are listed at the bottom of the results page.

# Usage

1. Install or start an instance of [Node-RED](https://nodered.org/#get-started).
2. Import the [AI Search flow](flows.json).
3. Open the **credentials** node and enter your own bearer token (in format `Bearer openaiapikeygoeshere`, using [your own OpenAI key](https://platform.openai.com/account/api-keys)).
4. Open the AI Search page (by default; [http://localhost:1880/aisearch/](http://localhost:1880/aisearch/)).
5. Type your search query, wait for the response and ask follow-up questions.

# Screenshots and video

This video shows an example of a search with follow-up questions:

https://user-images.githubusercontent.com/24693534/217353202-73e9c3d6-fb67-41f8-85b8-318d560b9b14.mp4

## Main search page

<img src="https://raw.githubusercontent.com/sjoerdvanderhoorn/aisearch/main/aisearch.png">

## Search examples
| Topic | Screenshot |
| --- | --- |
| "Chinese balloon" | <img src="https://raw.githubusercontent.com/sjoerdvanderhoorn/aisearch/main/chineseballoon.png"> |
| "Earthquake" | <img src="https://raw.githubusercontent.com/sjoerdvanderhoorn/aisearch/main/earthquake.png"> |
| "Tennis" | <img src="https://raw.githubusercontent.com/sjoerdvanderhoorn/aisearch/main/tennis.png"> |

