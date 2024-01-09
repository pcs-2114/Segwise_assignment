# Segwise_assignment
Solution of the assignment shared for the interview
[Google Colab](https://colab.research.google.com/) was used to write the assignment.<br>
You can download the Segwise_Assignment.ipynb file and upload into your colab to test the code.<br>
Please note that the input file that is expected is `playstore.csv`<br>
You can additionally use a file stored in your drive by mounting your drive. Please make sure your replace the file name with the path of the data csv file.<br>
Below is the schema of the input file that was shared with me. <br>
<br>

`_c0: integer (nullable = true)`<br>
`appId: string (nullable = true)`<br>
`developer: string (nullable = true)`<br>
`developerId: string (nullable = true)`<br>
`developerWebsite: string (nullable = true)`<br>
`free: integer (nullable = true)`<br>
`genre: string (nullable = true)`<br>
`genreId: string (nullable = true)`<br>
`inAppProductPrice: string (nullable = true)`<br>
`minInstalls: long (nullable = true)`<br>
`offersIAP: integer (nullable = true)`<br>
`originalPrice: string (nullable = true)`<br>
`price: double (nullable = true)`<br>
`ratings: integer (nullable = true)`<br>
`len screenshots: integer (nullable = true)`<br>
`adSupported: integer (nullable = true)`<br>
`containsAds: integer (nullable = true)`<br>
`reviews: integer (nullable = true)`<br>
`releasedDayYear: string (nullable = true)`<br>
`sale: integer (nullable = true)`<br>
`score: double (nullable = true)`<br>
`summary: string (nullable = true)`<br>
`title: string (nullable = true)`<br>
`updated: double (nullable = true)`<br>
`histogram1: integer (nullable = true)`<br>
`histogram2: integer (nullable = true)`<br>
`histogram3: integer (nullable = true)`<br>
`histogram4: integer (nullable = true)`<br>
`histogram5: integer (nullable = true)`<br>
`releasedDay: integer (nullable = true)`<br>
`releasedYear: integer (nullable = true)`<br>
`releasedMonth: string (nullable = true)`<br>
`dateUpdated: timestamp (nullable = true)`<br>
`minprice: string (nullable = true)`<br>
`maxprice: double (nullable = true)`<br>
`ParseReleasedDayYear: timestamp (nullable = true)`<br>

<br>
Please note that the following columns were used to aggregate the data <br>
<br>

`sale`<br> 
`free`<br> 
`genre`<br> 
`minInstalls`<br> 
`offersIAP`<br> 
`price`<br>  
`ratings`<br>
`adSupported`<br> 
`containsAds`<br> 
`reviews`<br> 
`score`<br>
`releasedYear`<br>
<br>
<br>
You can find the results in the results.csv file that is generated once the notebook is run.<br>
Please note that the results are not filtered with the 2 percernt threshold since the output had reasonable count. The code is available and commented.<br>
<br>
Your feedback is appriciated <br>
<br>
Thank you <br>
