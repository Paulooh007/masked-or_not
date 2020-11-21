The sample app described here is up at https://masked-or-not.herokuapp.com/. Test it out with face images with or without nose masks!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t masked-or_not . && docker run --rm -it -p 5000:5000 masked-or_not
```
