<h1>language-identifier</h1>
<p>Developed a recurrent neural network to classify six languages of different textbooks from scratch during my post-baccalaureate time at Knox College.</p>

<p>In this project, I worked with Professor Andrew Leahy to understand recurrent neural networks and their offshoot, long &amp; short-term memory. Then we built our own textbook database from Project Gutenberg using the top six languages: English, French, Finnish, Dutch, German, and Portuguese. We used 25,000 training data and 5,000 test data, and visually, our data was represented as a 3D tensor where the 1st dimension was the books; the 2nd dimension was the sentences, and the 3rd dimension was the characters (yes, we were doing character-level NLP).</p>

<p>We used the Keras LSTM model with (128, 64, 32) layers. After the 14th epoch, we reached a 96% validation accuracy. I saved the model as <code>model1.model</code> in the Model folder, and all data was saved as <code>.json</code> files.</p>

<p>Here is an example of the application of our model: </p>
<code>>>> Enter your sentence:
>>> Successful coaches at powerhouses have traditionally stayed put, "lording over fiefdoms until they lost their winning magic or were undone by age or scandal,"
>>> It is English</code>
