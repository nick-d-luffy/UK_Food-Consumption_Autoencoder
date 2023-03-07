# UK_Food-Consumption_Autoencoder
Ill be using a UK food consumption to analyse the Average eating habits between countries in the UK using Autoencoder

Ill create an encoder and decoder.

Combine the encoder and decoder to be an autoencoder and compile the model.

Create a MinMaxScaler to scale the data.  Ill Transpose the data, since we really have 17 feature columns and only 4 rows

Fit the autoencoder to the scaled data for 15 epochs..

Run the scaled data through only the encoder and predict the reduced dimensionalty output.

Join the encoded 2 dimensional data with the original countries index

 Plot out the results in a scatterplot to draw conclusion 
 
 Conclusion: Once we go back and look at the data in the table, this makes sense: the Northern Irish eat way more grams of fresh potatoes and way fewer of fresh fruits, cheese, fish and alcoholic drinks. It's a good sign that structure we've visualized reflects a big fact of real-world geography
