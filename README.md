Using Keras, start a jupyter notebook

```
docker run -d --name=keras -p=6006:6006 -p=8888:8888 -v=.:/srv gw000/keras-full
```

Download review data from `http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Movies_and_TV_5.json.gz` and unzip here.

Run `extract_reviews`

Go to `localhost:8888` and load the JTM notebook.

Train!
