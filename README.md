# Movie_Recommendation_System
What is recommendation system?
It is a filtration program whose prime goal is to predict the “rating” or “preference” of a user towards a domain-specific item or item.

Types of Recommendations system

![image](https://user-images.githubusercontent.com/26966629/171547590-08e87909-76da-4c6e-a580-6831bda045ac.png)


### Content based
This filtration method is based on the data provided about the products. The algorithm recommends products that are similar to the ones that a user has liked in the past.

#### Disadvantages
do not get much exposure to user
if user does not try different product buisness cannot expand

### Collaborative
This filtration method is based on the combination of the user’s behavior and comparing and contrasting that with other users’ behavior in the database. The history of all users plays an important role in this algorithm.

2 types of collaborative

  1. User-based Here we find similar past preference patterns This is achieved by making matrix of items 
  #### Disadvantages
    Taste of peope may change - Fickle-minded
    Users >>>> Items - hence difficult to maintain such large matrix
    Fake users may make our alogrithm biased

  2. Item-based find similar movies instead of similar users and then recommending similar movies to that ‘A’ has had in his/her past preferences 
  #### Advantages  over User-based
    Movie's don't change - like people's taste
    easier to maintian matrices of items
    movies cannot be fake

### Hybrid
Content + Collaborative
