# GardenPlanner
A text-based garden-planning application for North Carolina.

GardenPlanner.jar is a garden-planning application for North Carolina.  The user will select the North Carolina city closest to him.  The application will return an average last frost date for that particular city.  Then the user will select from a list of plants to plant.  

Each plant is an object and there is an array that will contain all plant objects.  Each plant has some variables or arrays containing the following:  
-days before the last frost date to plant that plant
-space between plants for optimum planting
-space between rows
-a string identifying whether the plant should be started indoors or outdoors
-an array of the plants that plant does well next to (companion plants)
-an array of the plants that the plant does not do well next to

Once the user selects a list of plants he wants to plant, the application determines an optimum starting date for that plant, based on the user's last frost date.  The application also displays the rest of the information stored in that plant object, including companion plants, whether to start indoors or outdoors, and the space between plants and rows.  
