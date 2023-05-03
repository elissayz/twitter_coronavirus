# Coronavirus twitter analysis

In this project I analyzed data from the Lambda Server that contains tweeted messages since 2013.In particular I analyzed the data from the year 2020, when the pandemic came into full effect across the world. In total, there are about 1.1 billion tweets in this dataset.

I used two main ways of dividing up the data. By country and by 

I then put this data together using the command
```

``` 
The following are the resulting graphs from running the visualization commands mentioned previously.

## Graphic Representation of #coronavirus by country

![#coronavirus by country](coronavirus_country.png)

### Graphic Representation of #코로나바이러 by country

![#코로나바이러 by country](#코로나바이러_country.png)

As we would expect, this hashtag was used mostly in Korea.

## Graphic Representation of #coronavirus by language

![#coronavirus by lang](coronavirus_lang.png)

### We can also see the representation of #코로나바이러 by language

![#코로나바이러by country](코로나바이러스_country.png)

Once again, since the language of the hashtag is Korean, we would expect it to be used 
most in that situation.

## Representation of #sick and #hospital

I then used the file `alternative_reduce.py`

The command

```
$ ./src/alternative_reduce.py --input_hashtags '#sick' '#hospital'
```
produces:

![#sick and #hospital through time](sick_hospital.png)

## Representation of #doctor and #nurse

Similarly, I generated this plot using alternative reduce. It documents the trends in the use of #doctor and #nurse through time.

![#doctor and #nurse in time](doctor_nurse.png)
