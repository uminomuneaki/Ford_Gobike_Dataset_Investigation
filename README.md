# Ford Gobike Dataset Investigation
## by Muneaki Umino


## Dataset

I used Ford Gobike ripdata(2017) available on  https://s3.amazonaws.com/baywheels-data/index.html
The data contains informations about where customer start riding Gobike, where they finished, duration, and user status(sustomer or subscriber).


## Summary of Findings

There was some interesting relationships between duration, distance and day, weekday, user_type.Users drive almost same distance from Monday to Sunday but much longer dulation on weekends. That indicates ther are users use Gobike for commute on weekdays, sightseeing on weekends. When I look at the relationship between categorical values, I became more confident on this idea because there are much more subscriber use Gobike on weekdays than weekends. This is a clear sign of users use Gobike for commute on weekdays for short and quick commute, after getting off metro. By doing multivariate exploration, I became pretty sure subscriber use Gobike for commute because they spend much less time than customers on any day. That means subscribers know where they are going. And multivariate charts strengthened my guessing even more, it shows travel distance for both customers and subscrivers are higher on weekdays. This trend clearly be seen especially on subscriber side.

## Key Insights for Presentation

I was able to show clear difference in duration, distance, each days, or user type. By visualizations, it became clearer that users drive shorter distance, shorter time on weekdays, and drive longer distance, longer time on weekends. 