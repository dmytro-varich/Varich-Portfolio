# 📚 Stack Explanation

A document explaining which technologies were used in each project and how they relate to my skills.


# 💻 Full-Stack Developer

## 1. [AI RESUME CREATOR](https://github.com/dmytro-varich/AI-Resume-Creator)

This is a full-stack web application developed as part of a university project for
the course Fundamentals of Cloud Technologies. The application parses data
from a given GitHub profile (with planned supportfor LinkedIn in the future) and
uses an AI-powered system to generate a personalized PDF resume based on
the provided information and the user's custom query.

**My Role:** Designed and developed the user interface and user experience of the application.

**Tech Stack:**

* **Frontend:** HTML, CSS, JavaScript, React, Tailwind CSS.
* **Backend / APIs:** fetch API (data fetching), localStorage.
* **Design & Prototyping:** Figma, Canva.
* **DevOps & Deployment:** Docker, Dockerfile, Nginx, Azure.
* **Document Handling:** pdfjsLib, Markdown.
* **Version Control:** Git.

**Acquired Skills:**

1. **Teamwork and Project Management**  
   The project involved teamwork, collaboration, and communication. The idea to create this specific application was mine, so the project is published on my GitHub. For task management and organization, we used the Projects tab on GitHub in a To-Do List format, where each team member assigned themselves tasks to complete. Git was used to push completed tasks to the repository.

2. **React Application and Web Server**  
   The initialization of HTML elements is dynamically rendered using React, and the application is served through the Nginx web server. The project uses components as well as React hooks: `useState`, `useRef`, and `useEffect`. For SVG elements, icons from the `react-icons` library sourced from the internet are used.

3. **Styling and Responsive Design**  
   I used CSS as well as Tailwind CSS for the website’s styling. The login window and alert notifications were sourced from the internet in Tailwind format. Additionally, the website is responsive and displays correctly on devices ranging from phones to large screens thanks to media queries and the application of responsive design principles, including the use of units such as `%`, `vw`, `vh`, `rem`, and `em`.

4. **Data Handling with Fetch and Storage**  
   `fetch` with POST and GET methods was used for sending and receiving data. `localStorage` was used to store information. The `pdfjsLib` library was used to load PDF files (for example, `await pdfjsLib.getDocument(URL.createObjectURL(pdfBlob))`).

5. **Containerization and Deployment**  
   A `Dockerfile` was created for local deployment, which sets up a folder, downloads necessary dependencies, copies files, configures the port, and runs commands. For deploying the frontend, I used Azure, hosting containers via Azure Container Registry and Azure App Service (PaaS). Using the terminal, I built the Docker image, authenticated and pushed the image to the registry, and then ran the container on Azure.

6. **Design and Documentation**  
   I used Figma to create the prototype of the web application layout and logo. I authored the documentation on GitHub in Markdown format, and the visual content for it was created using Canva.

## 2. [Website Demo Varich Journal](https://github.com/dmytro-varich/Website-Demo-Varich-Journal)
Semester project for the «Web Technologies» course (2nd year, TUKE). The goal of the project was to create a custom website based on an original concept, while completing a set of predefined tasks to develop practical web development skills. You can find the full list of requirements here. The chosen theme was a digital magazine, inspired by iconic publications such as GQ, Forbes, Vogue, and others.

**Tech Stack:**

* **Frontend:** HTML, CSS (responsive design, transitions, animations, transformations), JavaScript (DOM manipulation, form handling, validation, localStorage, AJAX).
* **Templating:** Template literals, Mustache.
* **SPA & Routing:** Client-side routing, Single Page Applications.
* **Features:** Dynamic content loading/editing, comments system, Google Sign-In integration.
* **Design:** Photoshop, Canva.
* **Documentation:** Markdown.

**Acquired Skills:**

1. **HTML & CSS**

   The website is built using HTML with various important tags (such as `nav`, `footer`, `main`, `article`, `template`, `table`, `svg`) and CSS with a wide range of properties, including transitions, animations, transformations, and responsive units such as `vh`, `vw`, `%`, `em`, and `rem`.

2. **JavaScript**

   JavaScript was implemented both directly in the HTML file for minor functionalities and in separate files, for example, for form handling, routing via hash (allowing a single page to switch between tabs on the client side), or rendering using templating engines such as Mustache, which enable rendering HTML pages with JavaScript. (Mustache is useful because it allows you to easily generate repeating blocks)

   The `fetch` function was used to interact with the server, including retrieving, updating, and adding various types of data such as comments, articles, and images. Additionally, `localStorage` was utilized to store information on the client side. 

   A Google Sign-In option was also added. To set up the Google Sign-In button, you need to go to Google Cloud, create a key for using Google login on your website, and specify your site's URL.

3. **Design**

   For creating visual content such as website logos, magazine covers, image editing, and more, **Photoshop** was used. For creating videos and mockups demonstrating website functionality, **Canva** was used. Documentation was written in **Markdown** format.

## 3. [Sentiment Analysis Web App](https://github.com/dmytro-varich/Sentiment-Analysis-Web-App)
This project focuses on Sentiment Analysis as part of an assignment for the
Fundamentals of Cloud Technologies course. The objective is to develop a
functional web application, analyze user input for sentiment (positive, neutral, or
negative), and later containerize the application using Docker.

* **Backend** performs sentiment analysis on the text submitted by the user.
* **Frontend** provides a user-friendly interface for interacting with the application.


**Tech Stack:**

* **Frontend:** HTML, CSS, JavaScript, Figma.
* **Backend:** Python, FastAPI, NLTK, dotenv.
* **DevOps:** Dockerfile, Shell.
* **Documentation:** Markdown.

**Acquired Skills:**

1. **Frontend & Backend**  
   The user interface is implemented using simple HTML and CSS. When the button is clicked, JavaScript sends a request to the backend, which is written in Python using FastAPI. The backend processes the request and performs sentiment analysis on the text using the NLTK library. Thus, the frontend interacts with the backend through an API, enabling dynamic application behavior.

2. **Containerization & Deployment**  
   The application runs locally using Dockerfiles written separately for the frontend and backend. Deployment was also performed on the Railway platform as a PaaS, utilizing Docker containers.
   

## 4. [Telegram Social Database](https://github.com/dmytro-varich/Telegram-Social-Network-Database)
Modeling the database structure based on an analysis of the Telegram
messenger. Developing an ER diagram and relational schema, and directly
creating the database using Oracle SQL language. Additionally, executing
queries and other commands to understand and demonstrate our knowledge
in practice.

**Tech Stack:**

* **Database Design & Modeling:** ER Diagrams, Relational Schema.
* **Database Implementation:** Oracle SQL, PL/SQL.
* **Documentation & Visualization:** Markdown, draw\.io.

**Acquired Skills:**

1. Creating tables using the `CREATE TABLE` command and assigning data types to columns such as `NUMBER`, `NUMBER(1)`, `VARCHAR2`, `TIMESTAMP`, `DATE`. Adding a foreign key using the syntax `FOREIGN KEY (user_id) REFERENCES Users(user_id)`.
2. Inserting data into a table is done using the command `INSERT INTO Users VALUES(...)`.
3. Deleting a table is performed with the command `DROP TABLE table_name`. Deleting all data from a table is done using the command `TRUNCATE TABLE table_name`.
4. To retrieve the result of a query, you need to execute the command:
   `SELECT attribute_name FROM table_name`
   You can also add a condition using `WHERE`, and use `ORDER BY` for sorting.

5. The method `CONCAT(attribute1, attribute2) AS final_attribute` allows you to combine values into one.
   The method `COUNT(attribute)` returns the number of rows matching the specified condition.

6. **JOIN** — operations for combining data from multiple tables:

   * `INNER JOIN` — returns only matching records from both tables.
   * `LEFT JOIN` — returns all records from the left table and the matching ones from the right (if there are no matches — `NULL`).
   * `RIGHT JOIN` — returns all records from the right table and the matching ones from the left.
   * `FULL JOIN` — returns all records, with matches displayed together and non-matches as `NULL`.
     Usage example:

   ```sql
   SELECT *
   FROM Table1
   INNER JOIN Table2
   ON Table1.id = Table2.id;
   ```

7. **HAVING** is used to filter data after grouping (`GROUP BY`).
   Example:

   ```sql
   SELECT department, COUNT(*) AS total
   FROM Employees
   GROUP BY department
   HAVING COUNT(*) > 5;
   ```
8. Nested subqueries are used to solve tasks where the result of one query is applied as a condition or a calculated field in another. This approach allows, for example, in the first case, to use a correlated subquery to count the number of messages for each user, and in the second — to select users who meet a complex condition: having folders with duplicate names. For such operations, constructs like `IN`, `EXISTS`, or expressions within `SELECT` are used, enabling flexible filtering conditions and aggregate calculations without unnecessary table joins.
9. Sequences and triggers are used to automate the generation of unique identifiers or other values during data operations. In this example, the sequence `user_id_seq` defines the rules for generating incremental user IDs, starting from a specific value and increasing by a fixed step. The trigger `User_Id_Trigger` is executed before inserting a new record into the `Users` table and assigns the next sequence value to the `user_id` field. This approach ensures consistency and uniqueness of identifiers without requiring manual input, streamlining the data insertion process.


# 📊 Data Science

## 1. [Business Analytics Course](https://github.com/dmytro-varich/Programming-Problems-Solutions/tree/main/university-assignments/tuke/business_analytics)

The Business Analytics course is a subject at TUKE University that includes applied and practical tasks for learning the fundamental stages of working with data.

**Tech Stack:**

* **Programming & Data Processing:** Python, pandas, NumPy, Jupyter Notebook, CSV, ZIP, SciPy, MLxtend.
* **Data Visualization:** Matplotlib, Seaborn, Data Visualization.
* **Machine Learning & AI:** scikit-learn, TensorFlow, CNN, Neural Networks, K-Means, KNN, Decision Tree, AgglomerativeClustering, Naive Bayes, Association Rules (Apriori).
* **Analytics & Modeling:** Data Preprocessing, Clustering, Regression, Evaluate, Descriptive Analytics, Predictive Analytics, Prescriptive Analytics.

**Acquired Skills:**

1. **Examination tasks** were applied assignments aimed at testing our knowledge. They usually followed a structure: data preprocessing, visualization, model training, and result analysis.

   * For example, reading files using `read_csv` and performing initial data inspection with methods like `head()` and `info()`.
   * To identify relationships between features, we built a **correlation matrix** (`df.corr()`), which shows the degree of dependency between attributes.

2. **Visualization** was performed using **Seaborn** and **Matplotlib** for building plots and charts — such as `boxplot`, `countplot`, and `hist`.

3. **Discretization of categories**:

   * using `pd.cut()`, for example:

     ```python
     df['quality_discrete'] = pd.cut(df['quality'], bins=3, labels=['low quality', 'medium quality', 'top quality'])
     ```

   * using `pd.qcut()`, which splits data into quantiles, useful when analyzing distributions.

4. **Feature scaling**:

   * for normalization, we applied `MinMaxScaler()`, which transforms values into a specified range (commonly between 0 and 1).

5. **Encoding categorical features** into numeric values for model training was done with `LabelEncoder()`.

6. **Splitting the dataset** into training and test sets was performed using `train_test_split`.

7. **Model training** typically followed a structure like:

   ```python
   model = CategoricalNB()
   model.fit(X_train, y_train)
   y_pred = model.predict(X_test)
   ```

8. **Model evaluation**:

   * visualizing the **confusion matrix** (`ConfusionMatrixDisplay.from_estimator(model, X_test, y_test)`), which shows TP, TN, FP, FN;
   * generating detailed metrics such as precision, recall, and F1-score with `classification_report(y_test, y_pred, target_names=target_names)`;
   * calculating regression error using **mean squared error** (`mean_squared_error(y_test, y_pred)`), which measures the deviation of predictions from the actual values.


## 2. [Neural Networks Learning](https://github.com/dmytro-varich/Programming-Problems-Solutions/tree/main/tutorials/neural_networks)

The Neural Networks course includes applied lessons conducted at TUKE University, as well as additional tutorials on image classification tasks.

**Tech Stack:**

* Python, Keras, TensorFlow, PyTorch.
* CNN (Classification & Recognition).
* OpenCV, NumPy.
* Data Preprocessing, Training Data, Data Separation.
* Linear Regression.
* Matplotlib, Visualization and Testing Data.
* Evaluate, Settings and Experiments.

**Acquired Skills:**

#### 1. Basics of PyTorch

During the course, I studied the fundamental features of **PyTorch**, including:

1. **Creating Tensors**

   * `torch.empty(x)` — initializes a scalar, vector, or matrix without filling values.
   * `torch.rand(size)` — creates a tensor with random values.
   * `torch.zeros(size)` — creates a tensor filled with zeros.
   * `torch.ones(size)` — creates a tensor filled with ones.
   * `torch.tensor([data], dtype=torch.float16)` — creates a tensor with a specified data type.

2. **Attributes and Properties**

   * `x.size` — tensor size.
   * `x.dtype` — data type.
   * To work with a tensor optimized for gradients, use:

     ```python
     torch.tensor([data], requires_grad=True)
     ```

3. **Tensor Operations**

   * Arithmetic operations: `+`, `-`, `*`, `/`.
   * Indexing and slicing: `x[1, :]` for a row, `x[1, 1].item()` for a single element.
   * Reshaping tensors: `x.view(size)`.

     * Using `-1`, e.g., `x.view(-1, n)`, lets PyTorch automatically determine the missing dimension.

4. **Integration with NumPy**

   * Example:

     ```python
     a = torch.ones(n)
     b = a.numpy()
     ```

   * Note: if a tensor and the converted NumPy array are stored in CPU memory, they share the same memory reference. Modifying one will affect the other.

5. **Working with GPU**

   * Check availability:

     ```python
     torch.cuda.is_available()
     ```

   * Define device:

     ```python
     device = torch.device("cuda")
     ```

   * Create tensor directly on GPU:

     ```python
     torch.ones_like(x, device=device)
     ```

   * Move existing tensor to GPU:

     ```python
     x.to(device)
     ```

## 3. [Computer Vision Course](https://github.com/dmytro-varich/Programming-Problems-Solutions/tree/main/university-assignments/tuke/computer_vision)

The Computer Vision course includes practical lessons at TUKE University with implementation of tasks in the field of computer vision, as well as exam assignments covering key topics.

**Tech Stack:**

* OpenCV, NumPy, Pandas, Matplotlib, SciPy, scikit-image, IPython.
* Hough Transformation, Kernel, Texture Segmentation, Color Segmentation, Fourier Transformation.
* Detection & Segmentation, Thresholding.
* Video Object Detection, Exposure, Morphology.

**Acquired Skills:**

## 4. [ML-AQ11-Rule-Generation](https://github.com/dmytro-varich/ML-AQ11-Rule-Generation)

Implementation of the AQ11 algorithm for rule generation in the field of machine learning. The primary task of this project is to classify whether a bank client will subscribe to a term deposit or not, taking into account crucial attributes such as age, occupation, education, and others.

### 🧠 How AQ11 Works

The AQ11 algorithm uses the concept of **inductive learning** to create rules that can classify new examples. The main stages of AQ11 are:

1. **Initialization**: Positive and negative examples are selected, serving as starting points for rule formation.
2. **Rule Generation**: A covering method is used to create rules that cover positive examples while minimizing coverage of negative examples.
3. **Refinement**: Rules are refined to improve accuracy and reduce overlap with other rules.
4. **Application**: The resulting rules are used to classify new data.

**Tech Stack:**

* **Programming & ML:** Python, ML Algorithms, pandas, scikit-learn
* **Data Handling & Preprocessing:** Preprocessing, Feature Extraction, Training, Evaluation
* **Datasets & Repositories:** UCI Machine Learning Repository
* **Documentation:** Markdown

**Acquired Skills:**

1. Gained experience in finding suitable datasets for my algorithms on platforms such as UCI Machine Learning Repository, Kaggle, and Hugging Face.
2. Implemented the main stages of the pipeline, including data preprocessing (data cleaning, feature selection, conversion to the proper format), splitting data into training and testing sets, implementing the algorithm, and evaluating its performance.
3. Documentation on GitHub was created using Markdown.