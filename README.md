# ProbLens

*The modern world demands individuals to equip themselves with coding skills. Algozenith, as an educational platform, assists learners on this journey by providing them with relevant coding problems to enhance their skills. However, with the plethora of coding platforms available, such as LeetCode, CodeChef, and Codeforces, navigating through the sea of coding problems can be daunting. The task at hand is to simplify this process by developing an efficient search engine.*

# Contains

The proposed search engine will be built around the TF-IDF algorithm to index coding problems efficiently. Users will be able to filter search results based on difficulty level and programming language. To accomplish this, the following steps will be undertaken:

- **Scraping problems** from different platforms such as LeetCode, Codeforces, and CodeChef using a Python-based web scraping tool like BeautifulSoup.
- **Implementing the TF-IDF algorithm** to handle search functionality.
- **Pre-processing the scraped data** to extract relevant text information.
- **Creating a dictionary of terms** from the data and calculating the inverse document frequency for each term.
- **Calculating the term frequency** for each problem and normalising it.
- **Applying the TF-IDF weighting scheme** to the data.
- **Implementing a query processing module.**
- **Designing the search engine's interface** using HTML, CSS, and JavaScript.
- **Integrating the search algorithm and server-side functionality** with the user interface.
- **Setting up a basic server** in Python using Flask or another suitable web framework.
- **Testing the search engine** for functionality and performance.
- **Refining and optimising the search engine** for a better user experience.