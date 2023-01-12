# Predicting-New-York-Taxi-Ride-Duration

<img src="https://github.com/owtwo/Predicting-New-York-Taxi-Ride-Duration/blob/main/images/TaxiNYC1-1600x960.jpg" style="float: left; width: 50%; margin-right: 5%; margin-bottom: 1em;">
<details>
        <summary>Context</summary>
        <br>
        <p style='text-align:justify;'>
          New York City taxi rides form the core of the traffic in the city of New York. The many rides taken every day by New Yorkers in the busy city can give us a             great idea of traffic times, road blockages, and so on. A typical taxi company faces a common problem of efficiently assigning the cabs to passengers so that           the service is hassle-free. One of the main issues is predicting the duration of the current ride so it can predict when the cab will be free for the next             trip. Here the data set contains various information regarding the taxi trips, its duration in New York City. We will apply different techniques here to get           insights into the data and determine how different variables are dependent on the Trip Duration. 
        </p>
</details>

<details>
        <summary>Objective</summary>
        <p style='text-align:justify;'>
          <ul>
            <li>To Build a predictive model, for predicting the duration for the taxi ride.</li>
            <li>Use Automated feature engineering to create new features</li>
          </ul>
        </p>
</details>

<details>
        <summary>Data Dictionary</summary>
        <br>
        <p style='text-align:justify;'>
          The <code>trips</code> dataset has the following information:   
        <ul>
          <li><code>id:</code> which uniquely identifies the trip
          <li><code>vendor_id:</code> is the taxi cab company - in our case study we have data from three different cab companies
          <li><code>pickup_datetime:</code> the time stamp for pickup
          <li><code>dropoff_datetime:</code> the time stamp for drop-off
          <li><code>passenger_count:</code> the number of passengers for the trip
          <li><code>trip_distance:</code> total distance of the trip in miles
          <li><code>pickup_longitude:</code> the longitude for pickup
          <li><code>pickup_latitude:</code> the latitude for pickup
          <li><code>dropoff_longitude:</code>the longitude of dropoff
          <li><code>dropoff_latitude:</code> the latitude of dropoff
          <li><code>payment_type:</code> a numeric code signifying how the passenger paid for the trip. 1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided
          <li><code>trip_duration:</code> this is the duration we would like to predict using other fields
          <li><code>pickup_neighborhood:</code> a one or two letter id of the neighborhood where the trip started
          <li><code>dropoff_neighborhood:</code> a one or two letter id of the neighborhood where the trip ended
        </ul>
        </p>
</details>

<details>
  <summary>Summary of key findings & insights</summary>
        <p style='text-align:justify;'>      
        <ul>
          <li><code>Trip_Distance</code> is the most important feature, which implies that the longer the trip is the longer the duration of the trip is.</li>
          <li> Features like <code>HOUR(dropoff_datetime)</code> and <code>HOUR(pickup_datetime)</code> seem to suggest that the hour in the day when pickups and dropoffs happen has an impact on the trip duration.</li>
          <li>Also the feature <code>dropoff_neighborhoods.latitude</code> and <code>pickup_neighborhoods.longitude</code> seems to suggest that trip duration is impacted by the dropoff and pickup locations. </li>
       </ul>
       </p>
</details>
