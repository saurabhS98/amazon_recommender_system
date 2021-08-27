# amazon_recommender_system
### Objective - Build a recommender system that recommends similar apparel items in eCommerce using text and image data
1. Scraped the data from amazon e-commerce using ‘auto scrap’ library
2. After cleaning we worked on 7 features (asin, brand, color, product_type_name, medium_image_url, title, formatted_price) out of 19 features and 28K objects
3. Finally taken 16K rows after deduping, and text pre-processing, out of 180k rows initially
4. In BoW, TF-IDF and W2V, W2V (word to vector)  showing grateful results
5. In visual features based on similarity we used CNN model (VGG16) that is showing good recommendation
6. All the models can be test ‘A|B testing’ techniques
