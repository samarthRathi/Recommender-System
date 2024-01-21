# Recommender Systems


What are **RECOMMENDER SYSTEMS**?

Recommender systems stand at the forefront of enhancing user interactions by offering personalized content or product suggestions tailored to individual preferences and behavior. These systems leverage advanced algorithms to analyze user data and generate relevant recommendations.

There are several types of recommender systems, each employing distinct algorithms and methodologies. The main types include:

1. **Collaborative Filtering:**
   - **User-Based Collaborative Filtering:** Recommends items based on the preferences of users with similar tastes.
   - **Item-Based Collaborative Filtering:** Suggests items similar to those preferred by a specific user.

2. **Content-Based Filtering:**
   - Analyzes the characteristics and features of items to recommend similar ones based on user preferences.

3. **Matrix Factorization:**
   - Decomposes the user-item interaction matrix to identify latent factors and make recommendations.

4. **Association Rule Mining:**
   - Identifies patterns and associations in user behavior to make suggestions based on historical data.

5. **Hybrid Recommender Systems:**
   - Combines multiple recommendation approaches, such as collaborative filtering and content-based filtering, to provide more accurate and diverse suggestions.

6. **Knowledge-Based Systems:**
   - Utilizes explicit knowledge about items and user preferences to generate personalized recommendations.

7. **Context-Aware Recommender Systems:**
   - Considers contextual information, such as time, location, or device, to tailor recommendations based on the user's current situation.

8. **Deep Learning Recommender Systems:**
   - Utilizes deep neural networks to model complex patterns and relationships in user behavior and preferences.

9. **Demographic-Based Recommender Systems:**
   - Considers demographic information, such as age, gender, or occupation, to make personalized recommendations.

10. **Multi-Armed Bandit Recommender Systems:**
    - Adapts recommendations over time by balancing exploration (trying new items) and exploitation (recommending known high-performing items).

The choice of recommender system depends on the nature of the data, user behavior, and the specific requirements of the application or platform. Hybrid approaches, combining multiple techniques, are often employed to capitalize on the strengths of different methods and improve overall recommendation accuracy.

### Context of this repository/project

E-commerce companies such as Amazon and Flipkart use a variety of recommendation systems to adapt to their consumers' tastes. Amazon, for example, uses item-item collaborative filtering, a strong technique capable of processing large datasets and generating high-quality real-time recommendations. This system serves as an information filter by anticipating and predicting user preferences and ratings. It demonstrates how e-commerce companies use novel techniques to improve customer experience through targeted suggestions.

## Dataset Information
* Source : https://jmcauley.ucsd.edu/data/amazon/

### Data Card - Attribute Information
* userId : Every user identified with a unique id (First Column)

* productId : Every product identified with a unique id(Second Column)

* Rating : Rating of the corresponding product by the corresponding user(Third Column)

* timestamp : Time of the rating ( Fourth Column)