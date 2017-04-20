## Clash Royale Deck Builder


### Architecture
This project has an Angular2 frontend that is supported by a Flask backend. The frontend will communicate with the backend through a REST API.

#### Classes
##### Angular2 
- Cards: this class will handle the parsing of the JSON containing the card information it recieves from Flask
- Deck: this class will handle the parsing of the JSON containing the deck builds it recieves from Flask

##### Flask
- will store the cards information and images and send that to Angular in a JSON
- will take the user input for average deck elixir and then build a normal distribution around that average elixir and randomly select 8 cards within some set standard deviation of the average elixir



```

