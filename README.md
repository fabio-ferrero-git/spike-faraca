## File 1:
# ```osm.ipynb```

This Jupyter Notebook demonstrates how to interact with OpenStreetMap (OSM) and a routing API to fetch and process geospatial data for the city of Turin.

### Features
- **Fetch OSM Data**:
Uses the Overpass API to retrieve monuments and fountains within a 5km radius of Turin's city center. Filters for elements with names and randomly selects 5 for display.


- **Routing Example**:
Demonstrates how to use the caresrouting.ontomap.eu API to compute a route for a set of jobs (locations) using a walking profile. The route steps are printed in a readable format.


### Usage
1. **Fetch Monuments and Fountains:**
Run the first code cell to query OSM and print 5 random named monuments or fountains in Turin.

2. **Get a Route:**
Run the routing example to see how to send a payload to the routing API and print the resulting steps


### How to Run
1. Open osm.ipynb in Jupyter Notebook or compatible IDE (e.g., PyCharm, VSCode).
2. Run the cells in order.


---

## File 2:
# ```gemma.ipynb```

This Jupyter Notebook provides a practical example of how to interact with Google's Gemma Large Language Model (LLM) using the google.genai Python client. It demonstrates basic usage patterns for sending prompts, handling multi-turn conversations, retrieving chat history, and streaming responses.

### Features
Connect to Gemma LLM:
Shows how to authenticate and create a chat session with the Gemma 3 27b-it model.


Multi-turn Conversations:
Demonstrates sending multiple messages in a conversation, maintaining context between turns.


Retrieve Chat History:
Illustrates how to access and print the full history of a chat session.


Streaming Responses:
Provides an example of receiving and printing streamed responses from the model for real-time output.


### Usage
- Set Up API Key:
Replace the placeholder API key with your own Google Gemini API key.

- Run the Notebook:
Execute the cells in order to:
1. Initialize the client and chat session.
2. Send messages and receive responses.
3. Access the chat history.
4. Try out streaming message responses.

- Explore Further:
Modify the prompts or experiment with different conversation flows to explore the capabilities of the Gemma LLM.

## NOTE: Documentation here https://ai.google.dev/gemini-api/docs/text-generation