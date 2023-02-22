# DDOS_Detection-and-Mitigarion-Using-ML and Entropy and RaspberryPi
In this work, 5 machine learning algorithms are used to develop a model that can automatically identify and mitigate DDoS assaults in SDN networks. All of the traffic flow entries are regularly collected by the model, which then extracts the native flow features and expands them by including additional features. A detection module uses five criteria to categorize each flow as normal or anomalous. When an attack is discovered, its source is prevented. Three ML algorithms were assessed with regard to the classification ML method utilized in the detection module, including random forest, Decision Tree, Logistic Regression, Naïve Bayes, and KNN. The outcomes of the experiment demonstrated that Random Forest is the best classifier for the generated network. Without disrupting regular traffic, the implemented methodology proved effective at swiftly and correctly identifying and thwarting threats.
Using Entropy we are able to detect the attack and for this we used POX Controller Instead of RYU.
## RESULTS
  <ul>
  <li>K Nearest Neighbors = 99.2% </li> 
  <li>Logistic Regression = 66.6%, </li>
  <li>Naïve Bayes = 71.41% </li>
  <li>Decision Tree = 99% </li> 
  <li>Random Forest = 99.7 % </li>
  </ul>
  
  
![1_JY1afR9MoaK-Ih3DnIQ7WA](https://user-images.githubusercontent.com/77917201/218697567-d3016189-f8c0-4a86-b47e-8abf8f78a349.gif)
