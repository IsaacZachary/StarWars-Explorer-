
<h1>Star Wars Explorer Shiny App</h1>
<nav>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li>
      <a href="#using-the-app">Using the App</a>
      <ul>
        <li>Description of the app and its purpose</li>
      </ul>
    </li>
    <li>
      <a href="#understanding-the-code">Understanding the code</a>
      <ul>
        <li>Description of the different files in the app</li>
      </ul>
    </li>
    <li>
      <a href="#app-interface">App Interface</a>
      <ul>
        <li>Input Options</li>
        <li>Film Information</li>
        <li>Species Information</li>
        <li>Output Tabs</li>
      </ul>
    </li>
    <li>
      <a href="#technologies-used">Technologies Used</a>
      <ul>
        <li>Description of the technologies used in building the app</li>
      </ul>
    </li>
    <li>
      <a href="#contributing">Contributing</a>
    </li>
    <li>
      <a href="#author">Author</a>
    </li>
    <li>
      <a href="#acknowledgements">Acknowledgements</a>
    </li>
    <li>
      <a href="#data">Data</a>
    </li>
    <li>
      <a href="#license">License</a>
    </li>
  </ol>
</nav>

<p>This is a Shiny App that allows users to explore data related to the Star Wars movies. Users can select different variables to plot and filter the data by different categories.</p>
<h2>Getting Started</h2>
<p>To run the Star Wars Explorer Shiny App locally, follow these steps:</p>
<ol>
  <li>Clone this repository to your local machine.</li>
  <pre><code>git clone https://github.com/&lt;your-username&gt;/star-wars-explorer-shiny-app.git</code></pre>
  <li>Open the app.R file in RStudio.</li>
  <li>Make sure you have the required packages installed. You can install them by running:</li>
  <pre><code>install.packages(c("shiny", "dplyr", "ggplot2"))</code></pre>
  <li>Run the app by clicking the Run App button in RStudio.</li>
</ol>
<h2>Using the App</h2>
<p>Once the app is running, follow these steps to use it:</p>
<ol>
  <li>Select the variable you want to plot from the dropdown menu.</li>
  <li>Select the category you want to filter the data by from the second dropdown menu.</li>
  <li>Use the slider to adjust the number of data points displayed in the plot.</li>
  <li>Explore the data by hovering over the plot points to view more information.</li>
</ol>
<p>The Star Wars Explorer Shiny app is an interactive and engaging way for users to explore various aspects of the Star Wars universe. The app was built using the Star Wars dataset from the Tidy Tuesday project, which contains information on characters, films, and species from the Star Wars franchise. As an aspiring DevOps Engineer with a passion for data science and machine learning, I built this app to showcase my skills in R and Shiny.</p>
<h2>Understanding the code</h2>
<p>The <code>ui.R</code> file defines the user interface of the app. It contains the dropdown menus and the output objects (summary table and scatterplot).</p>
<p>The <code>server.R</code> file defines the server logic of the app. It contains the code that retrieves the data, filters it based on the user inputs, and creates the summary table and scatterplot.</p>
<p>The <code>global.R</code> file loads and preprocesses the dataset.</p>
<h2>App Interface</h2>
<p>The app has a simple and user-friendly interface that consists of a sidebar panel and a main panel. The sidebar panel contains three input options, while the main panel displays the output based on the user's input. The app interface was designed with the end-user in mind, making it easy for anyone to navigate and use.</p>
<h3>Input Options</h3>
<p>Character Information:</p>
<p>The first input option allows the user to select a Star Wars character from a dropdown menu. Once a character is selected, the app displays information on the character's name, gender, height, mass, and homeworld. The app also displays a picture of the character, sourced from the Star Wars API. This option provides an easy way for users to learn more about their favorite Star Wars characters.</p>
  <h1>Film Information</h1>
  <p>The second input option allows the user to select a Star Wars film from a dropdown menu. Once a film is selected, the app displays information on the film's title, release date, director, and opening crawl. The app also displays a poster of the film, sourced from the Star Wars API. This option allows users to learn more about their favorite Star Wars films and explore the details that make them unique.</p>
  <h1>Species Information</h1>
  <p>The third input option allows the user to select a Star Wars species from a dropdown menu. Once a species is selected, the app displays information on the species' name, classification, designation, and language. The app also displays a picture of the species, sourced from the Star Wars API. This option provides users with a way to learn more about the different species in the Star Wars universe.</p>
  <h1>Output Tabs</h1>
  <p>In addition to the input options, the app also has two output tabs. The first output tab displays a scatterplot that shows the relationship between the height and mass of all Star Wars characters. The user can also filter the scatterplot by gender using a radio button. This tab allows users to explore the relationship between height and mass for their favorite Star Wars characters.</p>
  <p>The second output tab displays a bar chart that shows the number of films each Star Wars character appeared in. The user can also filter the bar chart by gender using a radio button. This tab allows users to explore which characters appeared in the most films and compare their appearances across different genders.</p>
  <h1>Technologies Used</h1>
  <p>The app was built using R and Shiny, along with the ggplot2 and dplyr packages. These technologies provide a powerful and flexible environment for data exploration and visualization. The Star Wars API was used to source the images and additional information used in the app.</p>
  <h1>Contributing</h1>
  <p>If you want to contribute to this app, you can:</p>
  <ul>
    <li>Add more visualizations to the app</li>
    <li>Improve the user interface</li>
    <li>Add more interactivity to the app</li>
    <li>Use a different dataset to create a similar app</li>
  </ul>
  	<h1>Author</h1>
	<p>The Star Wars Explorer Shiny app was created by Isaac Zachary, an aspiring DevOps Engineer with a background in Software Engineering and a passion for machine learning and data science. I recently completed my BSc in Software Development and currently work as a self-employed Software Support Consultant and Computer Trainer. This app was created as part of a project for a data visualization course, and I am eager to collaborate on exciting IT projects and share my knowledge in data science, AI, data analysis, and visualization in R and Python, which I am actively learning. You can reach me through my Gmail, Mobile, Work, or LinkedIn, listed below:</p>
 <ul>
	<li>👨‍💻 I’m an aspiring DevOps Engineer</li>
	<li>🤝 I’m open to collaborate on exciting IT projects and share my knowledge in datascience, AI, data analysis and visualization in R and python which I'm actively learning</li>
	<li>📫 How to reach me:</li>
	<ul>
		<li>📧 Gmail: isaaczachary18@gmail.com</li>
		<li>📱 Mobile: +254759325915</li>
		<li>🏢 Work: 254101029951</li>
		<li>👔 LinkedIn: <a href="https://www.linkedin.com/in/isaac-zachary-731a391a5">https://www.linkedin.com/in/isaac-zachary-731a391a5</a></li>
	</ul>
</ul>

<h2>Acknowledgments</h2>
<p>This app was created as part of a project for a data visualization course. The data used in this app was obtained from the Star Wars API. Special thanks to the creators and maintainers of these technologies and data sources for their contributions to the open-source community.</p>

<h2>Data</h2>
<p>The Star Wars survey dataset used in this app was obtained from FiveThirtyEight's GitHub repository: <a href="https://github.com/fivethirtyeight/data/tree/master/star-wars-survey">https://github.com/fivethirtyeight/data/tree/master/star-wars-survey</a></p>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the LICENSE.md file for details.</p>
