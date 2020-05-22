# HotelRec - LREC 2020

HotelRec, a very large-scale hotel recommendation dataset, based on TripAdvisor, containing 50 million reviews. For each review, we collected: the URL of the user’s profile and hotel, the date, the overall rating, the summary (i.e., the title of the review), the written text, and the multiple sub-ratings when
provided.

You can download the data [here](http://lia.epfl.ch/Datasets/Full_HotelRec.zip).

# Citation

Please cite our paper if you find the data helpful, thanks!

```
@InProceedings{antognini-faltings:2020:LREC1,
  author    = {Antognini, Diego  and  Faltings, Boi},
  title     = {HotelRec: a Novel Very Large-Scale Hotel Recommendation Dataset},
  booktitle      = {Proceedings of The 12th Language Resources and Evaluation Conference},
  month          = {May},
  year           = {2020},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {4917--4923},
  abstract  = {Today, recommender systems are an inevitable part of everyone's daily digital routine and are present on most internet platforms. State-of-the-art deep learning-based models require a large number of data to achieve their best performance. Many datasets fulfilling this criterion have been proposed for multiple domains, such as Amazon products, restaurants, or beers. However, works and datasets in the hotel domain are limited: the largest hotel review dataset is below the million samples. Additionally, the hotel domain suffers from a higher data sparsity than traditional recommendation datasets and therefore, traditional collaborative-filtering approaches cannot be applied to such data. In this paper, we propose HotelRec, a very large-scale hotel recommendation dataset, based on TripAdvisor, containing 50 million reviews. To the best of our knowledge, HotelRec is the largest publicly available dataset in the hotel domain (50M versus 0.9M) and additionally, the largest recommendation dataset in a single domain and with textual reviews (50M versus 22M). We release HotelRec for further research: https://github.com/Diego999/HotelRec.},
  url       = {https://www.aclweb.org/anthology/2020.lrec-1.605}
}
```

# Sample

```
{
   "hotel_url":"Hotel_Review-g194775-d1121769-Reviews-Hotel_Baltic-Giulianova_Province_of_Teramo_Abruzzo.html",
   "author":"ladispoli",
   "date":"2010-02-01T00:00:00",
   "rating":4.0,
   "title":"Great customer service",
   "text":"Great customer service and good restaurant service is what made this experience so wonderful for my family. Giulianuova is a pretty simple , not so \"wow\" town, with not very clean beaches as I was expecting when booking my reservation. What saved my vacation was staying at Baltic. Baltic is a very simple but functional hotel, but what makes it so special are the people that work there. It seems that as a part of their job training they had take some kind of class on humanity and spirituality, because the way they treat every single person with respect and smile is just amazing. Good job to the manager Massimo (who knows how to hire great people)!",
   "property_dict":{
      "sleep quality":4.0,
      "value":4.0,
      "rooms":3.0,
      "service":5.0,
      "cleanliness":3.0,
      "location":3.0
   }
}
```
