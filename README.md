# Movie-Recommendation-System
## Description
This project is a Movie Recommendation System built using Python. It provides personalized movie recommendations based on a user's favorite movie. The system uses **content-based filtering**, where movie metadata (e.g., genres, cast, director) is processed to identify similar movies. 

The core techniques involve **TF-IDF vectorization** and **cosine similarity** to calculate how closely related movies are based on their descriptive features. This project demonstrates how machine learning concepts can enhance user experiences in streaming platforms, e-commerce, and more.

---

## Features
1. **Content-Based Recommendation**:
   - Suggests movies based on attributes like genres, cast, director, and keywords.
   - Utilizes cosine similarity for finding similar movies.

2. **Interactive Input**:
   - Users can input their favorite movie, and the system will suggest the top 30 similar movies.

3. **Dynamic Metadata Processing**:
   - Combines multiple features (genres, cast, director, keywords, tagline) into a single descriptive text.

4. **Efficient Vectorization**:
   - Uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical vectors for similarity computation.

---

## Dataset
The project uses a dataset containing movie details such as:
- `title`: Name of the movie.
- `genres`: Movie genres (e.g., Action, Comedy).
- `cast`: Main actors.
- `director`: Director's name.
- `keywords`: Keywords describing the movie.

---

## Dependencies
Install the required Python libraries:
```bash
pip install pandas numpy scikit-learn matplotlib
