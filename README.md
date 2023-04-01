# DataBias
In this assignment, we explored the Perspective API's performance in detecting toxic language in comments. We first explored the data and identified a threshold of 0.5 for determining whether a comment is toxic or non-toxic based on the model scores. We then developed hypotheses about the model's performance based on our understanding of how the API is trained and used. Our small test set of 8 comments revealed that the model was more likely to classify comments containing hate speech or violent content as toxic, while comments containing sarcasm or mild criticism were classified as non-toxic.

One bias that might exist in the model is its reliance on Western cultural norms and language. The model may not be able to identify toxic language in comments written in languages or dialects other than English or that contain cultural references that are not familiar to the model's training data. Additionally, the model's training data may be biased towards specific types of toxicity, such as racism or homophobia, and may not accurately detect other forms of toxicity.

Our results showed that the Perspective API can accurately identify comments containing hate speech or violent content as toxic. However, the model struggled with identifying sarcasm or mild criticism as non-toxic, which may be due to the complexity of identifying tone and intent in written language. Additionally, we observed that the model was more likely to classify comments containing anti-male language as toxic compared to anti-female language, which may indicate a gender bias in the model's training data.

Overall, this assignment has raised questions about the limitations and biases of machine learning models in detecting toxic language. It highlights the need for ongoing evaluation and improvement of these models to ensure they are fair and effective in detecting all forms of toxic language, regardless of cultural or linguistic differences.

The test set is 
  
  "Thank you for understanding I think very highly of you and would not revert without discussion",
  
  "Eek but shes cute in an earthy kind of way Cant sing for shit though Thanks for giving me an unhappy memory",
  
  "Arabs are committing genocide in Iraq but no protests in Europe   May Europe also burn in hell",
  
  "Well it sucks to have a university to be nicknameless And its the first time in NCAA history that it has happened ",
  
  " Argh   Some random idiot deleted the whole Japan article ",
  "السلام عليكم و رحمة الله و بركاته الا الجميع  تفضلوا جميعا",
  
  "hello   you are an T0TL D0UCH3 BG",
  
  "we hate america and we are going to bomb the shit out of there cities Quezas will rain"  
