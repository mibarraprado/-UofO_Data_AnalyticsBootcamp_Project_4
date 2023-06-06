# Titanic
<h1>Spaceship Titanic</h1>

<p>Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four light years away and things aren't looking good.</p>

<p>The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.</p>

<p>While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!</p>

<p>To help rescue crews retrieve the lost passengers, we are to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.</p>

<p>Our task is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly.</p>

<p><strong>Help save them and change history!</strong></p>

<h2>Passenger Data Available:</h2>
<ul>
  <li>PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.</li>
  <li>HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.</li>
  <li>CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.</li>
  <li>Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.</li>
  <li>Destination - The planet the passenger will be debarking to.</li>
  <li>Age - The age of the passenger.</li>
  <li>VIP - Whether the passenger has paid for special VIP service during the voyage.</li>
  <li>RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.</li>
  <li>Name - The first and last names of the passenger.</li>
  <li>Transported - Whether the passenger was transported to another dimension.</li>
</ul>

LINK TO JSON KEY TO BE PLACED IN RESOURCES FOLDER: <a href="https://drive.google.com/file/d/1ensinFUUF8sbSE0vtFtu929srECWL7M2/view">Click here to view the file</a>

<h2>Directories:</h2>
<ul>
  <li><input type="checkbox" disabled> <b>Plots:</b> JPG files of all exploratory visualizations.</li>
  <li><input type="checkbox" disabled> <b>Resources:</b> CSV files for each SQL table, original data, and json file to access database with BigQuery.</li>
  <li><input type="checkbox" disabled> <b>cleaned_data:</b> A csv with original data cleaned and merged.</li>
</ul>
  <li><input type="checkbox" disabled> <b>Old Files:</b> impute_nans.ipynb, separate ML model files.</li>
</ul>

<h2>Files:</h2>
<ul>
  <li><input type="checkbox" disabled><b>space_neural_multiple_models.ipynb:</b> Predictions using neural network.</li>
  <li><input type="checkbox" disabled><b> sqltablecreation.ipynb:</b> Creating tables from source data for SQL database.</li>
    <li><input type="checkbox" disabled><b> Test_Models.ipynb:</b> Code for the following models: Logistic Regression, KNeighbors, and Random Forest.</li>
    <li><input type="checkbox" disabled><b> exploratory_analysis.ipynb:</b> Jupyter Notebook with exploratory data analysis and plots.</li>
      <li><input type="checkbox" disabled><b> Spaceship Titanic.pptx</b> Slide deck for presentation.</li>
